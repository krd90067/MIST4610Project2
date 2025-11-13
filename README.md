# MIST4610Project2

# Team Members
Pragnya Nallagonda: [@PragnyaNal] https://github.com/PragnyaNal   
Carter Trent: [@mct29403] https://github.com/mct29403   
Kohan Davis: [@krd90067] https://github.com/krd90067   
Eric Mied: [@ericmied] https://github.com/ericmied   
Vraj Patel: [@vrajpatel543] https://github.com/vrajpatel543   
Aiden Mintskovsky: [@aidenmint] https://github.com/aidenmint   

# Describing your dataset and what data it contains:
Group name: F25MIST4610_15058_Group1  
Data set describes Crime Data from 2020 to present from the LAPD obtained from https://catalog.data.gov/dataset/crime-data-from-2020-to-present.  
Dimesnsions: 1004991 rows, 28 columns  
Columns:    
  Division of Records Number: Official file number made up of a 2 digit year, area ID, and 5 digits. Data type: Number   
  Date reported. Data type: Date   
  Date occured. Data type: Date   
  Time occured. Data type: Number   
  Area: The LAPD has 21 Community Police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21. Data type: Number (whole)  
  Area name: The LAPD has 21 Community Police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21. Data type: String
  Report district number: A four-digit code that represents a sub-area within a Geographic Area. All crime records reference the "RD" that it occurred in for statistical comparisons. Find LAPD Reporting Districts on the LA City GeoHub at http://geohub.lacity.org/datasets/c4f83909b81d4786aa8ba8a74a4b4db1_4. Data type: Number (whole)   
  Part 1-2: . Data type: Number (whole)   
  Crime commited: Indicates the crime committed using a number and is the same as (Crime code 1). Data type: Number (whole)   
  Crime code description: Indicates the crime committed in words that correspondes to the value in the crime committed column. Data type: String   
  Modus Operandi: Activities associated with the suspect in commission of the crime.See attached PDF for list of MO Codes in numerical order. https://data.lacity.org/api/views/y8tr-7khq/files/3a967fbd-f210-4857-bc52-60230efe256c?download=true&filename=MO%20CODES%20(numerical%20order).pdf. Data type: String   
  Victim Age: 2 characters. Data type: Number (whole)   
  Victim Sex: F - Female, M - Male, x - Unknown. Data type: String   
  Victim Descent: A - Other Asian, B - Black, C - Chinese, D - Cambodian, F - Filipino, G - Guamanian, H - Hispanic/Latin/Mexican, I - American Indian/Alaskan Native, J - Japanese, K - Korean, L - Laotian, O - Other, P - Pacific Islander, S - Samoan, U - Hawaiian, V - Vietnamese, W - White, X - Unknown, Z - Asian Indian. Data type: String   
  Premis code: The type of structure, vehicle, or location where the crime took place expressed as a number. Data type: Number(whole)   
  Premis desciption: Indicates the premis in words that correspondes to the value in the premis code column. Data type: String   
  Weapon used code: type of weapon used in the crime identified by a number. Data type: Number (whole)   
  Weapon Description: Indicates the weapon in words that correspondes to the value in the weapon used code column. Data type: String   
  Status: Status of the case with 2 letters. (IC is the default). Data type: String   
  Status description: Defines the Status Code provided. Data type: String   
  Crime Code 1: Indicates the crime committed. Crime Code 1 is the primary and most serious one. Crime Code 2, 3, and 4 are respectively less serious offenses. Lower crime class numbers are more serious. Data type: Number (whole)   
  Crime Code 2: May contain a code for an additional crime, less serious than Crime Code 1. Data type: Number (whole)   
  Crime Code 3: May contain a code for an additional crime, less serious than Crime Code 2. Data type: Number (whole)   
  Crime Code 4: May contain a code for an additional crime, less serious than Crime Code 3. Data type: Number (whole)   
  Location: Street address of crime incident rounded to the nearest hundred block to maintain anonymity. Data type: String   
  Cross Street: Cross Street of rounded Address. Data type: String   
  Latitude: latitude where crime occured. Data type: Latitude   
  Longitude: longitude where crime occured. Data type: Longitude    
  
# The 2 questions the team generated and why they are interesting and important:
Question 1: How have overall crime patterns changed across Los Angeles neighborhoods from 2020 to 2024, and which areas have seen the most significant decreases in reported crime?   
Importance: This analysis focuses on detecting positive safety progress across the city and understanding what patterns or conditions may be linked to lower crime rates. Highlights neighborhoods where public safety initiatives or community changes are having measurable impact. Helps policymakers, residents, and law enforcement recognize successful crime-reduction areas for potential replication elsewhere. We use the dataset to examine how crime levels have evolved throughout Los Angeles since 2020 and identify neighborhoods that have experienced notable reductions in criminal activity.  
Question 2: Which neighborhoods in Los Angeles have the most dense crime and can be considered unsafe to live in?      
Importance: By comparing crime rates across neighborhoods, we can uncover patterns of safety, stability, and socioeconomic strength throughout the city. Highlights communities with strong safety records and social resilience. Reveals how income, education, and neighborhood development relate to crime reduction. Provides valuable insight for policy decisions, urban planning, and residents evaluating neighborhood safety. We use the dataset to identify and analyze the neighborhoods in Los Angeles that consistently report high levels of crime between 2020 and 2024.   

# The manipulations applied to the data set as part of the analysis:
Were there any manipulations or calculations that needed to be performed on the data, what were they, describe the purpose and how they were accomplished.   
Date reported and Date Occured columns data types needed to be changed from Date & Time to just Date. We also didn't include occurances from 2025 because we were reporting on change by year and we didn't have data for the entire year of 2025.   

# Analysis and Results:
Analyze and visualize the results of your analysis and describe the implications of your analysis.   
Please provide any citations if required as well as supporting visualizations and analysis generated from Tableau.   
Question 1: How have overall crime patterns changed across Los Angeles neighborhoods from 2020 to 2024, and which areas have seen the most significant decreases in reported crime?  
<img width="2400" height="1841" alt="image" src="https://github.com/user-attachments/assets/b7cc8f3f-cea5-4c5c-9582-3acbb27927bd" />
<img width="2400" height="1688" alt="image" src="https://github.com/user-attachments/assets/bfd5660a-b175-4d65-90b4-0d66d6d473f1" />
Crime was relatively low in 2020 and according to Pinkerton because of Covid lockdowns there was a sharp decrease in property and street crimes in 2020 due to reduced mobility and social interaction and after lockdowns ended in 2022 crime rates started to rise.  

Question 2: Which neighborhoods in Los Angeles have the most dense crime and can be considered unsafe to live in?  
<img width="2976" height="1887" alt="image" src="https://github.com/user-attachments/assets/413d4f52-e8d8-4a0a-9052-c65bfd809ae9" />
Central LA, 77th Street, Pacific, and Southwest Areas which can be seen more clearly on the below image from Google Maps have the highest crime rates.   
<img width="1794" height="1512" alt="image" src="https://github.com/user-attachments/assets/a6a2a238-d83c-4d4c-8d09-2f08a61d2d5b" />
The types of crime show that stolen vehicles and identity theft, burglary from a vehicle, and simple assualt are the most common.   
<img width="833" height="479" alt="image" src="https://github.com/user-attachments/assets/e11fe70d-a253-4929-a396-134d3d4da716" />

# Tableau Packaged Workbook
Save or Export your project as a Tableau packaged workbook file and provide it as part of the github repository.   
This group project is worth 12.5% of your final grade.
