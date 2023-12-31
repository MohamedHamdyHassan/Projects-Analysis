# Used Cars Price
____________________________

### Purpose
> #### --> A dataset containing all the required fields to build AI/ML models to find the price.

### Description
> #### --> 6019 records of used cars dataset, containing:
    -   Name
    -   Location
    -   Year
    -   Kilometers_Driven
    -   Fuel_Type
    -   Transmission
    -   Owner_Type
    -   Mileage
    -   Engine
    -   Power
    -   Seats
    -   New_Price
    -   Price

### EDA (Exploratory Data Analysis)

> #### --> Shape (6019,13) -->(5872,19)
> #### --> Data Cleaning:

>	-  Rename the columns.
>	-  Correction the datatype.
>	-  Deleting redundant columns
>	-  Cleaning individual columns

### Data Analysis
> #### --> Questions:

#####   1) What is the highst types of cars ?
##### 	2) What is the highst locations contain cars ?
#####	3) What is the highst year with cars ?
#####	4) What is the kilometers of the most cars ?
#####	5) What is the highst fuel type of cars ?
#####	6) What is the highst transmission of cars ?
#####	7) What is the highst location contains Auto/Manual cars ?
#####	8) Which transmission have more kilometer ?
#####	9) What is the highst owner type of cars ?
#####	10) What is the highst location with owner types ?
#####	11) What is the distribution of engine through years ?
#####	12) What is the relation between engine & power ?
#####	13) What is the locations that preferred high engines ?
#####	14) What is the distribution of power through years ?
#####	15) What is the highst car with seats and their kilometers and transmission ?
#####	16) What is the distribution of price through years and the relation with engine and power and seats ?

> #### --> Insights:

#####	1) There is a positive relationship between the target(Price) and (engine,power,year).
#####	2) The most 5 types of used cars:

>	- Mahindra XUV500 W8 2WD    
>	- Maruti Swift VDI            
>	- Honda City 1.5 S MT         
>	- Maruti Swift Dzire VDI       
>	- Maruti Ritz VDi              

#####	3) The most 5 locations that contain cars:

>	- Mumbai        
>	- Hyderabad     
>	- Kochi         
>	- Coimbatore    
>	- Pune          
 
#####	4) The highst year with used cars is 2014 followed by 2015 and the cars decrease after that because of the increasing of price of the cars. 
#####	5) The most of cars their kilometers are 60000KM.
#####	6) The weight of fuel type of cars with manual transmission is 99.03% diesel and 0.94% CNG and the Automatic is 100% diesel.
#####	7) The Highst location with Manual transmission is (Hyderabad) other wise the highst location with Automatic transmission is (Mumbai). 
#####	8) The kilometers of cars with Manual transmission are higher than Automatic transmission.
#####	9) The highst weight of owner type is first with(82.4%) followed by second(15.75%) and third(1.7%).
#####	10) The highst location with first owner type is Mumbai followed by Hyderabad and the highst location with second owner type is pune followed by chennai.
#####	11) We found the increasing of engines of cars through the years.
#####	12) The relation between engine and power is linear.
#####	13) The highst cars with kilometers are with 5 seats followed by 7.
#####	14) The price of cars increase through the years and the more the engine or power increases, the more the price increases.
#####	15) The expensive cars are with 2 seats followed by 4 seats.

### PreProcessing Data

>	- Feature engineering.
>	- Work with categorical data
>	- Detect and Handle Outliers
>	- train_test_split
>	- Scaling		