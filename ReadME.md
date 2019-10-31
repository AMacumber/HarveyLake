# Project: Harvey Lake

**Rationale**
This repository contains all the scripts (apart from ArcGIS) used for data analyses.

# Harvey Surface: Multi-site spatial analyses

## Cleaning_DataMerge (Python Script)
Merge ~760 CSVs representing hourly meteorological data from Fredericton A station from 1953-2015 from National Resources Canada database.

## Analysis_Frequency_WindData (Python Script)
Count the number of hours where the wind speed matches the Beaufort Wind Scale. Using the merged hourly meteorological data set (n = 552240) from Fredericton A station (1953-2015; National Resources Canada). Creates Table 2 of Chapter 1.

## Analysis_EMMA (Markdown R Script & PDF)
Details on end-member mixing analysis. Data wrangling and model selection/optimisation. Creates Table 3, Figure 7 and Figure S1 in Chapter 1.

## Analysis_Correlogram (Python Script)
Test correlation (Pearson) between various environmental parameters. Creates Table 4, Figure S2 and Figure S1 in Chapter 1.

## Results_EMMA_McClellandSlides (R Script)
Create a series of powerpoint slides that will illustrate the EMMA results incrementally.


# Harvey Core: HGC2

## Analysis_Chronology
The pdf contains the code and outputs (not age depth models) for Bayesian age-depth modelling using the BACON package in R and subsequent evaluation of the models. As the BACON package requires interaction during the modeling process it is not possible to show the outputted models.

## Analysis_Chronology_Comparison
Compared the total chronological error (max median date - min median date) of the 14C-only chronology and the 14C+Hurricane chronology. I also compared the change in age at each depth between the two chronologies.

## Analysis_ECDF_WeatherData
I wanted to compare the weather stations to see if they were giving similar results.

## Analysis_EMMA (Markdown R Script & PDF)
This pdf contains the code and outputs (except output of Figure 3 due to poor formatting) for EMMA using EMMAgeo package in R.
