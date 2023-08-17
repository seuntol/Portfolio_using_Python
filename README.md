# Portfolio_using_Python
This project aims to understudy the trends of fertility and life expectancy rate in canada over the period 1960-2010. It will involve dissecting our dataset using python and employ Power BI to produce visulaization of our findings. The trend can be helpful in gaining several insights such as population insights, proxy for potential impact of economy or health deveopment on the population, explanation on the ageing population and high rate of immigration needs and many other insight. The visulaization helps us easily see at a glance the changes over the years.

# Data
There is a folder containing the our data sources. It includes three excel sheets: Country_Metadata, Fertility_Rate and LifeExpectancy_At_Birth.

# Tools
The project used python on visual studio code, Microsoft Excel, Power Query and Power BI.

# Steps followed
## Data Extraction and Transformation (the codes can be found in the code file)
The raw data was loaded into the visual studio code following the following steps:
  - The data was uploaded into my github through the update file
  - I linked to the visual studio code by creating a barnch under my code menu and proceeding
  - I imported pandas and numpy then employed openyxl to import the data to load my excel workbook
  - I set my maximum column and created a function to create a dataframe for each excel sheet
  - I imported islice from intertools and created a worksheet to carry several transfromation on my dataframe
  - I created headers, reset index, changed columns name, melted columns, change type from text to integers, merged, created columns, averages before finally saving the newly developed data frames in an excel format to download back into my local drive.
  - The newly created data frames are df_region, df_country and df_canada
    
## Data Loading into PowerBI
  - I imported the newly created dataframe above into my PowerBI
  - I used power query to do some basic editing before finally loading such as decimal reduction and removing index column
  - On PowerBI
    - i employed the line graph to show the trend of fertility and Life Exoectancy over the years
    - I used the score card to show the average of both life expectancy and fertility over the period.

# Outcome
While fertility rate has dropped over the years, life expectancy as increased. This is one of the explanation for the population having more aged people than young people and the high rate of immigration requirements in the country. We the availability of other data sources such as medical, education, economy, we may test for trends between them and our two variables in this study. Advance statistical tools could be used to check for correlation and make predcitions nad reccomendations. 

