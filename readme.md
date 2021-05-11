#QGIS : MAPPING THE SPATIAL DISTRIBUTION OF HEALTH INSURANCE COVERAGE IN PENNSYLVANIA 

##DAT 241: Final Project


## Abstract
Health Insurance Coverage is one of the important metric of mesuring the overall America's well being. Whether there is illness, injury or preventive needs, health insurance provides a greater access to medical care, a protection from high unexpeced cost and more economic stability.

## Purpose: 
The overall goal of this project is to be able to geolocate vulnerable Track/Counties with the lowest Health Insurance coverage for the State of Pennsylvania. Without having the pretention to be an Expert Analyst, I strongly believe that such study could be immensly helpful for policy making, because driven by a strong, reliable, and credible source in this Case(ACS). 

## As an Inquiry Question, it could be formulated as follows: What are the Tracks or Counties in the state of Pennsylvania with the lowest health insurance coverage?


## Background/Rationale 
The Dataset taken from the United States Census Bureau provides a clear spatial distribution of the Health insurance coverage for state of pensylvania based on different income levels. For this project we narrowed it down to only 03 main incomes levels:

1.1 Looking at the Coverage for Folks making Under $25,00 a yers(low Income Target): Classified as Segment 1(<$25,000)

1.1 Coverage for Pennsylvenians Making between $25,000 to $49,999 (Middle Income Target): Classified as Segment 2(<=50,000)

1.1 Coverage for people making around $75,000 or between $50,000 to $74,999 (High bound/Target): Segment 3

### Sources:

1.1 General Household Survey:
[ACS: American Census Data](https://data.census.gov/cedsci/advanced?t=Health%20Insurance&g=0400000US42.140000&d=ACS%205-Year%20Estimates%20Detailed%20Tables) Five Year Estimates

1.1 Employment/Income Survey:
[CSP: Current Population Survey](https://www.census.gov/programs-surveys/cps/data.html)

1.1 Longitudinal Survey:
[SIPP: Survey of Icome and Program Participation]((https://www.census.gov/programs-surveys/sipp/data/datasets.html))

## Analysis Steps

11. Data Acquisition: Downloaded the raw data from United Census Bureau(Filtered By Topic, Tracks, and Estimates)

11. Data Filtering/Cleaning: I narrowed down to only the fiels and Columns of interest

11. Defined Main Segments: (03) to be Specific
    - Classified as **Segment 1(<$25,000)**
    - Classified as **Segment 2(Between $25,000 to $49,999)**
    - Classified as **Segment 2(Between $49,999 to $74,999)**

11. Imported the Pennsylvania Tracts Shapefile Into QGIS

11. Process some Joins: Pennsylvania Tracks with the CSV Trimmed Dataset 

11. Performed some Computations: In this Case Health Insurance Rate Calculations by Segment

### Work Process Log


## Results and Discussion

## Conclusion

## Limitations

## Future Research