# Phase 1 : (C) Consumer Profile Master Data

Over here we require only one csv file :

04_c_wm_stores_single_precision_(created_csv) 


CSV files:

05_c_user_profile_[(created_csv) using_faker],

06_c_user_address_[(created_csv) using_faker],

07_c_user_vehicle_[(created_csv) using_faker]  are created using faker.

-------------------------------------------------------------------------------------------------------------------------------------------------

 #### Over here, we are  Making the User  infos in the form of Functions in order to call these functions whenever required.
 
 User Info , Family Members Info , Marital Status , Kids , Credit Card Details , User Income  Group , Vehicle Details , User Address.
 
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
 
 #### After creating the Location Data , We are Combining User Profile and family with the User Location Data  to create  MASTER  DATA
 
 #### By Creating Record(s) into DataFrame. Over 100 records generated for each of the 52 States.
 
 #### We then save the 3 Master Data for further references in the project.
 
 ##### •	User Profile

 ##### •	User Address

 ##### •	User Vehicle
 
 
