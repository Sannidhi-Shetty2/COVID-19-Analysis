##  <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/126ceca9-e69e-43b4-851a-9de69526d082" width="48" height="48"> COVID-19-Analysis
This project aims to analyze the COVID-19 pandemic using publicly available data. The project includes a Jupyter notebook with Python code to extract, clean, and visualize COVID-19 data from various sources. Additionally, the project provides a dashboard to interactively explore the data.
##  <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual**

| Files/Folder| Description |
| ------------- | ------------- |
| **Dataset Folder** | This folder provides data state wise and district wise data in csv format |
| **Python File** | This contains the .ipynb file of the analysis for Data Extract and Data cleaning.  |
| **MySQL File** | This contains the .sql file for the exploratory data analysis.  |

<br>

<p align="center"><img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/178dce48-6221-49b3-b2a2-d553c8f9bcdd" width="400" ></p>

##  <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/8e952995-c32d-4703-a9dd-92d1914cc6d9"  width="48" height="48"> Analysis
   
### o	Highest number of confirmed and deceased cases were seen in Maharashtra.

<img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/76644cc3-ed14-4172-8957-3c0f2d7b79a4" width="600" >

### o	October month had the highest number of total confirmed cases.

<img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/de470e60-0c1a-48d3-9424-96354b0e298c" width="700" >

### o	Highest Vaccination rate observed in in Sikkim.

<img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/2930d151-66db-4238-b596-1ace0541ff6b" width="700" >

### o	Lowest Vaccination rate is observed in Uttar Pradesh.
    
### o	Dadra and Nagar Haveli has the highest Recovery Rate.
    
### o	October has the Highest deceased cases.
    
 <br>       
 

## <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/1f211524-e1d5-46be-a421-2662597281d7" width="48" height="48" > Quick Start



### 1. Import the data from API using requests library.

    
### 2. The imported data was in json format hence we used json library to read the data.

<img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/7243d01e-9b32-43b6-9ae4-b3f6ba3ba9a8" width="1000" >
    
### 3. We looked for null values and replaced it with zero, looked for duplicates.
    
### 4. Stated analysing the data by using pandas function like groupby, sort_values etc.
    
### 5. Used nested 'for' loops to extract the relevant data from the nested dictionary.

<img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/6331248c-c475-4797-a680-89fd8465a082" width="1000" >
    
### 6. Extracted the individual state data from dataframe in csv format and imported data into MySQL.
    
### 7. Aggregated the distribution by month and week wise for each state.
    
### 8. Imported the aggregated data into Excel for further Analysis.
    


##  <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/126ceca9-e69e-43b4-851a-9de69526d082" width="48" height="48"> Dashboard
 <p align="center"><img src="https://github.com/AmitKotnala/Covid19AnalysisIndia/assets/118646525/cfda519c-cc24-4df2-b6db-d827dd845b7a" width="1000" ></p>
