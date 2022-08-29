# Phase 1 : (B) Consumer Data Generation

Over here we Generate the User Master Dataset that includes 

User Info , Family Members Info , Marital Status , Kids , Credit Card Details , User Income  Group , Vehicle Details , User Address 

--------------------------------------------------------------------------------------------------------------------------------


Over here we require the two csv files :
 
 02_c_selected_stores_(created_csv) 
 
 04_c_wm_stores_single_precision_(created_csv) 
 
using 02_c csv file, 04_c csv file is created

--------------------------------------------------------------------------------------------------------------------------------

#### To Generate the Artificial Business Data, We are gonna create the specific User Data manually step by step 
#### using 'FAKER' , a Python package that wiil randomly generate fake/dummy data for you.   


•	User Info : [ Name , DOB , Age , Phone Number , SSN , UUID , Family ID (10 char) ]

•	Job Specific Info : [ Job Type , Company Name , Company Address]

•	Family Members Info : [  UUID , Family ID (10 char) , Family Name,  Name , DOB , Age , Phone Number , SSN  ]

•	Marital Status : [ Married or Single ]

•	Kids : [ No kids to 3 Kids Max. , UUID , Family ID (10 char) , Family Name,  Name , DOB , Age ]

•	Credit Card Details : [ Credit Card type Provider , Credit Card Number , Security Code (CVV) and the Expiry Date ] 

•	User Income  Group : [ Based on Annual Income earned ]

•	Vehicle Details : Add the VehicleProvider to your Faker instance: from faker import Faker from faker_vehicle import VehicleProvider

faker_vehicle is a provider for the Faker Python package.It provides vehicle and machinery related fake data .

[ Vehicle Maker , Vehicle Model , Vehicle Make  Year , Vehicle  Model Category And many more ]


•	User Address : [ Street Address , City , State , Zip ,  Code , Latitude , Longitude ]

### Using WALMART Location Geographical Data (Longitude and Latitude) we can generate the User Address within the close proximitiy in the same city, zipcode ### where the store is using ' FAKER '.

-------------------------------------------------------------------------------------------------------------------------------------------------------

## Showing Walmart and User Address in Map

### 1 (a)

![Screenshot (148)](https://user-images.githubusercontent.com/103312836/186493226-1297b5df-2fcc-4179-bece-c3279b0ae79a.png)

### 1 (b)

![Screenshot (133)](https://user-images.githubusercontent.com/103312836/186493398-d915e871-c00d-475b-af6c-b58ce4070140.png)

### 2 

![Screenshot (134)](https://user-images.githubusercontent.com/103312836/186494120-fc66478a-9ede-40f4-b022-3973e55aa6b2.png)

### 3 (a)

![Screenshot (137)](https://user-images.githubusercontent.com/103312836/186494216-2f0a056c-b510-4f2d-9b33-10b4892ae321.png)

### 3 (b)

![Screenshot (136)](https://user-images.githubusercontent.com/103312836/186494289-d6532c6d-dea1-4058-af1b-300f83d8c4a6.png)


