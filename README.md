# Apartment Pricing Analysis in Deagu District,South Korea



## Business Understanding
  ### Overview
  World over, home ownership has become elusive for the average citizen. 
  Some people claim that the COVID-19 pandemic is to blame for the sharp increase of house prices but affordability was a major concern even before the pandemic. According to Realestatewitch, home prices have jumped a cumulative 118% since 1965 even after accounting for inflation. 

  In this project, we seek to understand the factors that determine the cost of a house using Data from Daegu district in Korea. 

## Problem Statement

  Housing has become an expensive endeavor world over and research shows that prices often do not match the features of the house. 

  Accurate pricing of property is necessary to ensure efficient and effective decision making. 

  The regression model will determine the value of houses given various characteristics of the house as well as the neighborhood as the major determinants of the price of the house.

  The model will also indicate which of the characteristics are most influential in the pricing of houses. This way, buying and pricing of houses will become an easier venture not only for the buyers but also sellers. 

## Proposed solution
  This project seeks to find out the factors that influence pricing of apartments. By looking at the feature variables such as nearness to social amenities, number of floors, type of management etc., valuable insights can be provided to stakeholders such as the government and regulators for better policy formulation and decision making especially in this day and age when the pricing of apartments has become untenable. 

  Ideally, this solution should protect the consumer and prepare them for any eventualities in their quest to acquire an apartment. 

### Justification
  This analysis will uncover some of the factors that influence pricing of apartments and by doing so, provide real estate companies and their consumers with insight so they can make more informed decisions. 

### Main Objective
  Build a regression model that gives an accurate regression analysis of house prices within the Daegu city in South Korea. This model will be built upon the variables extracted from the given dataset. 
## Specific Objectives 
    1.To determine the type of management that runs the most expensive apartment.

    2.To determine the effect of size of apartment on the price.

    3.To determine how proximity to social amenities e.g school, hospital, department store, public office and subway affect the price of an apartment. 

    4.To determine the effect of properties of house e.g. floors, hallway type, and heating type affect the price of an apartment.

    5.To determine the effect of shared resources e.g number of elevators, parking lot, and facilities on the price of an apartment. 

    6.To determine which month is likely to have the most sales of houses.

    7.To determine how long after being built a house is sold. 


## Research questions

  Some research questions to be looked into when undertaking the project include the following : 

    1.What are the most important factors affecting the pricing of houses?

    2.Is there a specific time of the year when houses are bought?

    3.What is the range of prices of houses?

    4.Has the price of housing generally gone up/down over the years?


## Resources
### Personnel

The project was handled by a team of 5 Data Science Students:
  Peter Kirimi

  Rachel Juma

  David Kiplang’at

  Farnadis Kanja

  Ted Kimani 

## Datasets

  This dataset was sourced from HouseDataLink.
  It has 5800 observations and 30 columns. Collected over a time period of 10 years traded apartment detailed data using API provided from data.go.kr
## Assumptions

  The data is a true representation of actual prices of houses in Daegu, Korea. The data was collected by the Korean government 

## Constraints

  The data is from Korea which is not a good representation of the Kenyan landscape.
  In that sense, the context was a bit difficult to understand. The way of life and how the commercial construction industry operates is very different from the researcher’s 

## Project Plan 

  The project plan was as follows : 


 # DATA UNDERSTANDING


 ## Data understanding overview

  There is one dataset available for this project. It is a csv file.
  We have provided a detailed description for the dataset that we’re working with.

  ## Data Dictionary 


    1 SalePrice
    2 Price in USD
    3 YearBuilt-This is the year in which the apartment  was built
    4 YrSold-This is the year in which the apartment  was sold
    5 MonthSol-This is the month in which the apartment was sold 
    6 Size(sqf)-Size of the apt in square feet
    7 Floor-what floor is property located
    8 HallwayType-Type of hallway terraced or mixed
    9 HeatingType-The type of heating in the house either central or individual 
    10 AptManageType-type of how apartment was managed by
    11 N_Parkinglot(Ground)-count number of parking spaces on the ground
    12 N_Parkinglot(Basement)-count number of parking spaces on basement
    13 TimeToBusStop-measure time takes from apartment to bus stop (categorical)
    14 TimeToSubway-measure time takes from apartment to subway station (categorical)
    15 N_APT-number of apartment building in a apartment complex
    16 N_manager-number of people manage apartment facilities (eg. security, cleaner etc)
    17 N_elevators-Total number of elevators in an apartment complex
    18 SubwayStation-name of subway station nearby apartment
    19 N_FacilitiesNearBy(PublicOffice)-Number of public offices near the apartment
    20 N_FacilitiesNearBy(Hospital)-Number of hospitals near the apartment
    21 N_FacilitiesNearBy(DptStore)
    22 N_FacilitiesNearBy(Mall)-Number of malls  near the apartment
    23 N_FacilitiesNearBy(ETC)-Number of other offices near the apartment eg hotels and special school
    24 N_FacilitiesNearBy(Park)-Number of parks near the apartment
    25 N_SchoolNearBy(Elementary)-Number of elementary schools near the apartment
    26 N_SchoolNearBy(Middle)-Number of middle schools near the apartment
    27 N_SchoolNearBy(High)-Number of high schools near the apartment
    28 N_SchoolNearBy(University)-Number of university schools near the apartment
    29 N_FacilitiesInApt-number of facilities for residents like swimming pool, gym, play ground
    30 N_FacilitiesNearBy(Total)-total number of facilities nearby apartment
    31 N_SchoolNearBy(Total)-total number of schools nearby apartment


