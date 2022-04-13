# UK HPI (House Price Index) Analysis - Python
Data Analytics Project about the evolution of the house prices in the UK by Javier Sanchez Agesta

## Objective

This repository contains the analysis of the house prices' evoloution across the different regions in the UK from 1995 till present, based on the sale prices of all the different kind of homes and differentiating by old, new, detached, semi-detached, terraced, or flat, as well as if it has been sold by mortgage or cash. 

Through the project we will try to find out what is the trend of the price sales, if there is stationarity and if there is any other factors that affect the prices of the houses, as well as if those factors are common to the different types of living spaces. 

## Data

The data set has been downloaded from the official website of the UK Government, www.gov.uk, in the Home section. The UK HPI captures changes in the value of residential properties. 

- It includes all residential properties purchased for market value in the UK. The dataset contains the sale price of the property, the date when the sale was completed, full address details, the type of property (such as detached, semi-detached, terraced or flat), if it is a newly built property or an established residential building and a variable to indicate if the property has been purchased as a financed transaction (for example using a mortgage) or as a non-financed transaction (cash purchase). 

- Index SA and Average Prices SA show the seasonally adjusted variables for a geography in a particular period. 

- FTB and FOO data indicate whether the transactions were relating to First Time Buyers (FTB) or Former Occupier Owners(FOO).

- Data is available at a national and regional level, as well as counties, local authorities and London boroughs. 

The full details of the data are available [here](https://www.gov.uk/government/statistical-data-sets/uk-house-price-index-data-downloads-december-2021)

### Data Limitations & Ethical Considerations

In terms of the collection and processing of the data, the UK HPI is not as timely in publishing as other house price index measures published in the UK. This is because it is based on completed sales at the end of the conveyancing process, rather than advertised or approved prices. As sales only appear in the UK HPI once the purchases have been registered, there can be a delay before transactions feed into the index. As such, caution is advised when interpreting price changes in the most recent periods as they can be revised. 

Another limitation is the availability of data. From 1968 to 1994, the only data available is divided by regions, more specifically East Midlands, England, London, Northern Ireland, Scotland, South West, United Kingdom, Wales, West Midlands Region, Yorkshire the Humber. For this reason, four our tests and comparisons we will base our analysis in these major areas, although we will keep the counties data for further specific analysis.

In terms of ethical limitations, the full address details have been suppressed to comply with the European GDPR, in a way that no data could be specifically related to any individual. Data is publicly available and the use is allowed with educational purposes, so we are good to go ahead with our analysis.

## Tools 

For this project the following Python libraries were used:

-	Pandas - for data analysis

-	Seaborn - for visualization

- Matplotlib - for visualizations

- Sklearn - for k-means algorithms

- Datetime - for time series data
 
## Folders contents

The repository is divided in 4 sections, defined as follows:

1. Project Management: Data Project brief document containing information and descriptions of main aspects of our analysis, such as 'Objective', 'Context', 'Data requirements', 'Analysis criteria', 'Dashboard requirements' and 'Project deliverables'

2. Data: folder containing the pieces of data used for this project, as well as the ones resulting after cleaning and wrangling.

3. Scripts: this folder contains the Jupyter notebooks created for this analysis, including cleaning and wrangling the data, consistency checks,  subsetting and creating new variables, data visualization, time series analysis, and machine learning realted processes.

4. Analysis - Visualizations: in this folder we can find the main visualizations produced through the analysis with Seaborn and maplotlib. 


