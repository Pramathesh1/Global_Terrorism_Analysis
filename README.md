# Global Terrorism Analysis
The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.

The Project focuses on exploring and analyzing the data to discover key findings pertaining to terrorist activities.

## Introduction
Terrorism, a widespread global threat involving violence and fear tactics by individuals or groups to achieve political or ideological aims, wreaks havoc not only through loss of life but also through economic devastation. From direct destruction of property to market unease, xenophobia, and tourism decline, terrorism inflicts significant economic hardship. Understanding past attacks through analysis is crucial for improving counter-terrorism efforts and potentially preventing future tragedies.

This Exploratory data analysis project involves analysis of the global terrorism data between 1970 to 2017, providing insights on the attacks conducted in different years and in different countries. We show the violent terrorist groups in the world, their attack types and their places of operations. We also analyze attacks in India over the years, in different states, the most active terrorist groups and their areas of operations.

## Data Summary
The dataset has one csv file named “Global Terrorism Data.csv”. The csv file has 1,81,691 rows and 135 columns. The rows represent a particular incident of a terrorist attack identified by the 1st column “eventid”. The project does not involve an analysis on all of the 135 column or variables. The following are the column names or variables which are used in the project along with its description.

'eventid'          : Serial number of a particular incident, useful to keep count of incidents

'iyear'            : year of the incident

'imonth'           : month of the incident

'iday'             : day of the incident

'country_txt'      : country in which the incident occurred

'region_txt'       : region in which the incident occurred

'provstate'        : state or province of the country in which the incident occurred  

'summary'          : summary of the incident, when available

'alternative_txt'  : type of attack if it was not terrorist for certain

'attacktype1_txt'  : general method of attack used (i.e. assassination, hijacking, bombing/explosion, etc.)

'targtype1_txt'    : general type of target/victim (i.e. business, government, police, military, etc.)

'gname'            : terrorist group responsible for the attack

'target1'          : specific person, building, installation, etc. that was targeted

'nkill'            : number of dead 

'nwound'           : number of wounded

'property'         : was property damaged during the attack?

'propextent_txt'   : type of property damage (major, minor or catastrophic in terms of monetary value)

'latitude'         : latitude of the incident

'longitude'        : longitude of the incident

## Tools used in EDA

### Matplotlib
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. One of the greatest benefits of visualization is that it allows us visual access to huge amounts of data in easily digestible visuals. Matplotlib consists of several plots like line, bar, scatter, histogram, etc.

### Pandas
Pandas is an open-source library that is made mainly for working with relational or labeled data. DataFrame is the most important and widely used data structure and is a standard way to store data. DataFrame has data aligned in rows and columns like a spreadsheet database. We import the CSV file “Global Terrorism Data.csv” into a dataframe using pandas method read_csv() to begin the analysis.

### Geopandas
GeoPandas module makes working with geospatial data in python easier. GeoPandas is based on the pandas. It extends pandas data types to include geometry columns and perform spatial operations. It combines the capabilities of pandas and shapely, providing geospatial operations in pandas and a high-level interface to multiple geometries to shapely. Geospatial data describe objects, events, or other features with respect to a location (coordinates) of the earth.

## Exploratory Data Analysis
We have divided the EDA into 2 parts. 

### Analysis on World data
•	Timeline of terrorist attacks

•	Countries and Regions with most attacks

•	Terrorist organizations with most number of attacks.

•	Insurgencies.

•	Most lethal attacks.

•	Deadliest type of attack

•	Comparing Terrorism in Middle East and Latin America

### Analysis on India data 
•	Timeline of Indian attacks

•	States with most number of attacks

•	States with most insurgencies

•	Jammu and Kashmir terrorism timeline

•	Deadliest type of attacks in India

•	Terrorists' Targets in India

•	Terrorist Organizations with most number of attacks

•	Indian states affected by Maoism

## Conclusion
1.	Before 2000s, global terrorist activities remained comparatively lower than period after 2000s which reached peak in 2014. Although since then, drop in terrorist activities is seen but still it is higher than any other time period. Kills per attacks ratio which were at high during late 90s and early 2000s has reduced after 2007. 1970s were the most peaceful period.
2.	Regions of Asia and Middle East & North Africa saw most no. of terrorist activities. Australasia & Oceania is the most peaceful region. Iraq saw the most attacks as a country.
3.	Terrorist organizations of Islamic State of Iraq and the Levant (ISIL) and Taliban have conducted most no. of terrorist activities. Boko Haram has the highest Kills per attack ratio.
4.	Iraq tops the list of countries with most insurgency attacks.
5.	Regions of Middle East & North Africa and Latin America had a contrasting trend in terrorism where Latin America had most of the terrorism in 1980s and early 1990s which subdued later, Middle East & North Africa saw the rise in terrorism mainly after 2000.
6.	Terrorism in India increased after mid 1980s. Since 2007, attacks have increased drastically. However, India has managed to keep the death count low in recent times compared to period before 2007.
7.	Jammu & Kashmir has seen the most no. of terrorist attacks and most no. of insurgency attacks among the Indian states, particularly after 1989.
8.	Armed Assault and Bombing/Explosion are the types of attacks that have taken most lives globally and also in India.
9.	Maoist groups have had the most no. of terrorist attacks in India. They have operated mostly in Eastern states of Chhattisgarh, Jharkhand, Odisha and Bihar.
