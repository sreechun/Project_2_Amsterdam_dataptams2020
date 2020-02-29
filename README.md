<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Pollution in Amsterdam 
## A focus on 2 neighbourhoods
*[Eva Doñaque & Sreelatha Chunduri ]*

*[Data Analytics, Part-time 2020, Amsterdam]*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description
Our project focuses on the effect of pollutants on people in different neighbourhoods of Amsterdam. Elevated concentrations of air pollutants, such as sulphur dioxide (SO2), nitrogen dioxide (NO2) and particulate matter (PM10 and PM2.5) have adverse effects on human health. For our current study we chose to study the trend of 3 pollutants that includes NO2, PM2.5 and PM10 in Amsterdam.

We initially identified the following 4 neighbourhoods where we had data of the 3 pollutants from 2012 through 2019.
1. Einsteinweg - A10 West
2. Van Diemenstraat
3. Vondelpark
4. Stadhouderskade

After an initail data analysis we chose Einsteinweg and Vondelpark to study deeper and understand the effects of pollutants and the associated trends.


## Questions & Hypotheses
Q1. Is there a decrease in pollution from 2012 through 2019 because of new policies?
Q2. Is one neighbourhood's pollution level better than the other neighbourhood?

Hypothesis: 
1. Traffic (all types of vehicles inclusing bicycles) emissions are directly propotional to the air quality and increase in hybrid cars and assocaited policies have reduced the pollution.
2. The increase in green spaces helps in the improvement in the air quality of the neighbourhoods.

Findings:
Our findings have proven that our first hypothesis is False and the second one is True.

## Dataset
What dataset (or datasets) did you use? What is the source of your data? Provide links to the data if available and describe the data briefly.

Our dataset includes the following:
1. CSV files of pollutants measured in microgram/m3 for all the areas in Netherlands from 2012 through 2019- https://www.luchtmeetnet.nl/rapportages
2. CSV file of the total number of vehicles (all types) in Amsterdam from 2000 through 2019 - https://www.ois.amsterdam.nl/downloads/xlsx/2019_jaarboek_411.xlsx


## Database

Our database includes CSV files seperated by semicolon in some cases and colon in other cases. The data includes the pollutant information from the entire NL. We cleaned, filtered and merged the data using pandas and identified 4 common enighbourhoods to conduct our analysis. Among the 4 neighbourhoods we chose 2 neighbourhoods to do in-depth analysis.



## Workflow

1. Download the CSV files from the online database for the 3 pollutants from 2012 through 2019. The pollutants include NO2, PM2.5 and PM10. There is no pollution data before the year 2012 and after the year 2019. So, we chose that as our starting and ending years.
2. Import and Clean the information from the database and put it in a dataframe.
3. Rename the columns and rows and delete all the unwanted neighbourhoods. Only pick Amsterdam neighbourhoods among a big list of all the neighbourhoods in NL.
4. After filtering only the Amsterdam neighbourhoods, identify the neighbourhoods that are common in all the 3 pollutants. Delete the remaining neighbourhoods.
5. Now using different dataframe applications (Pandas) analyze the data.
6. Download the total number of vehicles from 2000 through 2019 from Amsterdam database. Import, clean and analyze the data to see a trend (increase or decrease) of the vehicles in Amsterdam.
7. Conduct research on the bicycle usage and green areas in the 2 chosen neighbourhoods of Amsterdam.
8. Identify a corelation between  the pollutants, green spaces, and vehicles and prove/disprove the hypothesis.


What does your repository look like? Explain your folder and file structure.

## Links

[Repository](https://github.com/)  
[Slides](https://slides.com/)  

