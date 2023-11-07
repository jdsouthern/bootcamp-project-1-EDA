
# Analysis
## Levar McKnight

The Charlotte-Mecklenburg Police Department categorizes criminal offenses into 72 categories, including a category for "Other Unlisted Non-Criminal" incidents.  Though this non-criminal category ranked as the first or second highest category throughout most of the years coverd in the dataset, CMPD advised that it should not be included in the analysis of criminal incidents.
The categories of crimes were listed under the column named "Highest NIBRS Description", named after the National Incident-Based Reporting System.  
- The crime that occurred the most annually was Theft from Motor Vehicle followed closely by All Other Offenses.
- In 2019, Theft from Motor Vehicle peaked at 10,375 before dropping to 8,464 the following year.
- Shoplifting peaked in 2019, also and continues to decline.
- Shoplifting, Theft from Motor Vehicle, Burglary, and All Other Thefts decreased once Covid hit.

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

