

# Visualisation and Analyzation of The Novel Coronavirus (2019-nCoV) Dataset

### Abstract

  The novel coronavirus (COVID-19) that was first reported at the end of 2019 has impacted almost every aspect of life as we know it. Since, having methods to visualize and visually analyze a big data makes it easier to comprehend the data, never before has visualisation been more important than in the COVID-19 pandemic. In this project, we present a big data visualization for visualizing and analyzing the COVID-19 epidemiological data. 


### Introduction

  SARS-CoV-2 is a virus that is the cause of a serious life-threatening disease known as COVID-19. It was first noted to have occurred in Wuhan, China in November 2019 and the WHO reported the first case on December 31, 2019. The outbreak was declared a global pandemic on March 11, 2020 and by May 30, 2020, a total of 5 899 866 positive cases were registered including 364 891 deaths.

  The Covid-19 vaccine has changed the course of the pandemic. In total, 162 doses have been given for every 100 people around the world. In countries that reached the highest levels of vaccination, death rates plummeted. Over a year into the biggest vaccination campaign in history, more than 12.7 billion doses have been administered across 184 countries. 

  However, the COVID-19 patterns are sometimes contradictory and this is where visualizations come in. This project focuses on covid cases at different time stamps and vaccination status worldwide.

### Dataset Description

We will be working with 2 datasets:
1) **Coronavirus Dataset**:  The dataset contains the daily summary of Coronavirus cases (confirmed, death, and recovered), by state/province

The dataset has the following columns :

*   date - The date of the observation, using Date class
*   province - Name of province/state, for countries where data is provided split across multiple provinces/states
*   country - Name of country/region
*   lat - The latitude code
*   long - The longitude code
*   type - An indicator for the type of cases (confirmed, death, recovered)
*   cases - Number of cases on given date
*   uid - Country code
*   province_state - Province or state if applicable
*   iso2 - Officially assigned country code identifiers with two-letter
*   iso3 - Officially assigned country code identifiers with three-letter
*   code3 - UN country code
*   fips - Federal Information Processing Standards code that uniquely identifies counties within the USA
*   combined_key - Country and province (if applicable)
*   population - Country or province population
*   continent_name - Continent name
*   continent_code - Continent code 

2) **Vaccination Dataset**: The dataset contains data about population in selected countries and territories worldwide that had received a COVID-19 vaccination as of December 14, 2020

This dataset includes the following columns:

*   country_region - Country or region name
*   date - Data collection date in YYYY-MM-DD format
*   doses_admin - Cumulative number of doses administered. When a vaccine requires multiple doses, each one is counted independently
*   people_partially_vaccinated - Cumulative number of people who received at least one vaccine dose. When the person receives a prescribed second dose, it is not counted twice
*   people_fully_vaccinated - Cumulative number of people who received all prescribed doses necessary to be considered fully vaccinated
*   report_date_string - Data report date in YYYY-MM-DD format
*   uid - Country code
*   province_state - Province or state if applicable
*   iso2 - Officially assigned country code identifiers with two-letter
*   iso3 - Officially assigned country code identifiers with three-letter
*   code3 - UN country code
*   fips - Federal Information Processing Standards code that uniquely identifies counties within the USA
*   lat - Latitude
*   long - Longitude
*   combined_key - Country and province (if applicable)
*   population - Country or province population
*   continent_name - Continent name
*   continent_code - Continent code

### Graphical presentation of Key variables

Please click on the link given above to view the dashboard.


### Summary of Analysis

I have plotted the following :

*  Total Covid Cases Region-wise
*  Relationship Between cumulative Active v/s cumulative Death Cases and cumulative Active v/s cumulative Recovered Cases
*  Relationship Between cumulative Recovered and cumulative Death Cases
*  Confirmed Cases Worldwide
*  Active Cases Worldwide
*  Recovered Cases Worldwide
*  Death Cases Worldwide
*  cumulative COVID-19 cases in the 5 most affected countries
*  Partially Vaccinated Ratio Plot of different Countries
*  Fully Vaccinated Ratio Plot of different Countries

### Conclusion

We observed that initially death cases increase more rapidly as compared to recovered cases whereas rate of recovery is slower initially compared to rate of increase in the active total. Also we observe a linear trend while we plotted the cumulative Recovered and cumulative Death Cases.
