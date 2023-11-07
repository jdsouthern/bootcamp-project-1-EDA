# Analysis

## Levar McKnight

### Analysis of the Most Common Crimes in Charlotte (2017 -2023)

The Charlotte-Mecklenburg Police Department categorizes criminal offenses into 72 categories, including a category for "Other Unlisted Non-Criminal" incidents.  Though this non-criminal category ranked as the first or second highest category throughout most of the years covered in the dataset, CMPD advised that it should not be included in the analysis of criminal incidents.
The categories of crimes were listed under the column named "Highest NIBRS Description", named after the National Incident-Based Reporting System.  

The slide labeled “Most Common Criminal Offenses by Year” illustrates the number of offenses reported in Charlotte in the past several years.  CMPD categorizes theses offenses into 72 types.  Many of these types have had double-digit, or even single-digit figures over the years.  To simplify the graph only the top ten criminal offenses that had more than 2,000 incidents in any given year were chosen to be displayed.  One category labeled “Other Unlisted Non-Criminal” was omitted from the top ten because CMPD suggested that an analysis of criminal incident reports should not include non-criminal incidents.

The crime that occurred the most annually was Theft from Motor Vehicle followed closely by “All Other Offenses”.  Theft from Motor Vehicle peaked in 2019 as did Shoplifting.  One interesting observation is that motor vehicle theft represented by the brown line was relatively stable throughout most of the years, but then shot up in 2022 and 2023.  According to CMPD, the spike is caused by a social media trend called the “Kia Challenge” that started in the summer of 2022.  In 2023, Kia and Hyundai thefts rose by 1,747%.  Overall, most offenses depicted had a significant drop in 2020, with Theft from Motor Vehicle having the steepest drop.  This shows that the COVID mandates had a significant impact on crime in the Charlotte area.

## Jake's Analysis
### Place Type Crime Count Chart
This chart was produced by changing values of 72 unique crime types and generalizing them into 7 unique types. Some of the insights that can be gained from this chart are as follows. Financial crimes almost never occur in open or public areas. Most cases of retail crimes are theft. Theft occurs more in residential areas than commercial and retail combined.Residential areas appear to be the most at risk of criminal activity.‘Theft’, ‘Violent Crime’, or ‘Other’ incidents  make up 88% of the recorded incidents.

### Efficiency/Case Clear Charts
To generate these charts I took the reported dates of the end of the incident and the case closing date for all closed cases in the data set, and used a funtion to subtract them and find the difference in number of days. Then I took a mean and median of the data grouped by the precinct to get an idea of how the data was distributed for each precinct. Each precinct has a skewed right distribution showing that a few outlier cases that take a long time to clear are fairly commonplace for the CMPD. Among the precincts, 'Airport' has by far the fastest closing times in terms of mean and median. 'South' has the highest median closing time, but a relatively normal average showing it has the closest to a normal distrobution. 'University City' has the highest average at nearly double the next hightest number of days, showing that it must have some fairly extreme outliers compared to its other precincts.

## Project 1- Kyndall's Analysis

In our project we decided to search for a dataset relating to crime. We were able to locate the Charlotte Mecklenburg Police Department's incident reports from 2015 to present day. We then came up with a list of questions for our hypothesis from looking over that data. 
When glancing over the data we got a pretty good indication that Covid affected many different types of incidents in Charlotte and hereafter. We were able to effectivly clean up unusable data in order to make our dataset into something we could loop through to figure out the questions to our dataset.

Finding the total incidents in Charlotte from 2017 to present day
In order to be able to build an adequate line chart to represent all of Charlotte I first had to create a dictionary to account for all the misspelled versions of Charlotte. There was 62 total initially from Matthews to Huntersville that I decided to categorize into 'OTHER'. For all misrepresentations of Charlotte I switched over to 'Charlotte".
I then incorporated the new dictionary, built the new date format to be able to read through the dataset. Then I looped all incidents from 2017 to end of 2022. I built a line chart to account for the rise and fall of crimes in Charlotte and took out all of the 'OTHER' cities attached to it to get the most accurate.

## Dante Dillahunt
Crime and Location
Bar Graph Crime Location by Year and Location
crimeTable with LOCATION_TYPE_DESCRIPTION


Look at how COVID affected crime in Mecklenburg County. We choose the years 2017 through 2023 with May 2019 being the year of COVID.

Purple
Parking lot was trending up two years before COVID with an average of 12,804per year.  Parking lot crimes started trending down to 12,372 during COVID and started trending back up after COVID reaching a high in 2022 at 14,156 crimes.

 Blue
Indoors crimes have the highest number of crimes of the data cycle averaging 41,000 crimes per year.  Indoor crimes trended down to 38,598 during COVID but started to trend up in 2022 to 41399 and started dropping again in 2023.

Orange
Other Crimes has trended up in 2017 at 2046, to 2633 during COVID where it continued to trend up until 2022 at 32937 crimes per year.

Green
Outdoor crimes were trending up averaging 34,703 crimes per year, until COVID, in which the trend dropped to 32,269. Outdoor crimes continued to drop with a one-year spike in 2022 at 32,328.

Red
Parking Deck crime has been very inconsistent year to year, but overall data shows that there is an upper trend in park deck crimes.

Overall crimes went down during COVID except for Other Crimes and Parking Deck crimes.

