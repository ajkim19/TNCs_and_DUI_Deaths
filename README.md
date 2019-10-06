# Do TNCs Affect DUI Deaths?

## Background

### Transportation Network Company (TNC)
* Also known as mobility service provider (MSP) or ride-hailing service
* Defined as a company that uses an online-enabled platform to connect passengers with drivers using their personal, non-commercial vehicles
* Provide service to areas that do not have taxis normally available
* Charging lower rates than taxicabs
* Companies that we've observed: Lyft, Uber

### Lyft
* By 2013, Lyft was providing 30,000 rides a week
* By the end of 2013, it hits 2.7 million completed rides
* April 2014, Lyft had become available in 60 U.S. cities
* By the end of 2014, they hit 18.1 million completed rides

![Lyft Annual Completed Rides](https://github.com/ajkim19/TNCs_and_DUI_Deaths/blob/master/Resources/Lyft%20Annual%20Complete%20Rides.png)

### Uber
* In July 2012, the company introduced UberX, using non-luxury vehicles
* By early 2013, the service was operating in 35 cities as well as allowed drivers to use their personal vehicles
* From a base of near zero in mid-2012, more than 160,000 drivers actively partnered with Uber at the end of 2014 in the United States

![Uber Number of Active Driver-Partners](https://github.com/ajkim19/TNCs_and_DUI_Deaths/blob/master/Resources/Uber%20Number%20of%20Active%20Driver-Partners.png)

### DUI
* Driving under the influence (DUI) occurs when a person operates a motor vehicle while intoxicated
* Men are most likely to be involved in this type of crash, with 4 male drunk drivers for every female drunk driver
* The highest percentage of drunk drivers were 21- to 24-year-olds, at 27 percent, followed by 25- to 34-year-olds, at 26 percent.

## Objective

Our project was to look at the relationship between given information on TNCs and the number of DUI deaths.
* Was there an immediate impact on DUI deaths with the introduction of TNCs?
* Which gender has the highest death rates, and which had the highest impact?
* Which age group has the highest death rates, and which had the highest impact?

To display our finding, we used Python, Pandas, and Matplotlib

## Data
Our data was obtained from data.gov.

![data.gov]()

![data_screenshot1]()

Because the data that we obtained was already fairly clean, not much data munging was required. We removed and renames some of the columns, and replaced null values with the value "0" (information on the dataset stated that null values were given to negligible values).

![data_screenshot2]()

After cleaning the data, we used Matplotlib to visualize our data.

![data_screenshot3]()


### Findings

## DUI Deaths by State (2012)
* Used to compare Gender by States
* Men in North Dakota had the highest rate of deaths
* Men in Utah had the lowest rate of deaths
* Women in Montana had the highest rate of deaths
* Women in West Virginia had the lowest rate of deaths

## DUI Deaths by State (2014)
* Used to compare Gender by States
* Men in Wyoming had the highest rate of deaths
* Men in New York had the lowest rate of deaths
* Women in Montana had the highest rate of deaths
* Women in New York had the lowest rate of deaths

## DUI Deaths by Year
* Men have much higher rates of deaths in both years
* 10% decrease in deaths for Males in 2014
* Little to no change in deaths for Women in 2014
* Men account for 84% of all DUI deaths in 2012
** 83% in 2014

## DUI Deaths by State (2012)
Ages 21-34 had the highest rates
Highest in Montana
Lowest in Massachusetts
Ages 0-20 had the lowest rates
Highest in South Carolina
Lowest in New York
Ages 35+
Highest in North Dakota
Lowest in New Mexico

## DUI Deaths by State (2014)
Ages 21-34 had the highest rates
Highest in Montana
Lowest in New Hampshire
Ages 0-20 had the lowest rates
Highest in Mississippi
Lowest in Illinois
Ages 35+
Highest in Wyoming
Lowest in New Hampshire

## DUI Deaths by Year

14% reduction of deaths
For Ages 21-34
Generation most impacted by TNCs
53% reduction of deaths 
For Ages 0-20
Small reduction of deaths
For Ages 35+

### Discussion
Men have higher rates of DUI deaths than women
However little correlation between Female DUI deaths and TNCs
Ages 21-34 had the highest rates as well as the highest correlation
Overall, correlation between DUI deaths and TNCs
Introduction of Uber/Lyft in 2012 caused a slight reduction in deaths


### Post Mortem
Unable to find APIs with the data we needed
Difficulty finding the best way to separate the data for analysis
Issues having our graphs represent our data the way we wanted
Beneficial to analyze later years as popularity of TNCs increased


