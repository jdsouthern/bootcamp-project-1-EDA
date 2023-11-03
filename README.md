Kristina's Analysis

In this project we searched for a dataset and created questions that acted as a hypothesis.
We came across a public dataset made available by Charlotte listed Incident Reports starting in 2015 and going up to the present day.

Looking through all of this info, we realized we could get a pretty good read on how Covid affected reported incidents CMPD (Charlotte Mecklenburg Police Department).
We began by doing an initial cleanup of the data, removing columns that would not be as useful in our task to find answers.
Things like X and Y Coordinates, Latitude and Longitude, and City, as all of these incidents occurred in Charlotte.
So once the data was cleaned up a bit in the CSV, I read it into Jupyter, and would continue to clean if needed from inside of Jupyter.

My initial task was to find which time of day crime occurs most and least, as it appeared at first glance that there were timestamps recorded in this dataset.
However, all of the time stamps were marked with correct dates, but none were marked with actual times of the day. Each input for 'Date Reported' had a time of 00:00:00+00.
To try and work around this, I decided to see which divisions in CMPD had the most and least amount of crime annually.
In the making of the DataFrame using Pandas, I discovered that more cleaning of the data needed to be done. I removed 'Huntersville', 'Davidson', and 'Unknown' from our data.
Looking into CMPD divisions, I discovered there are 13 Divisions within CMPD, and that neither 'Huntersville' nor 'Davidson' are actually CMPD divisions, which explained the low number of incident reports that was skewing data. These two locations were removed from the dataset in a further cleaning effort, as to only include the actual divisions that CMPD has jurisdiction over.

Once the data was ready, I created a line chart using MatPlotLib to visualize the DataFrame and specifically the number of incident reports by each CMPD division.
As for which division has the least number of incident reports, Airport had the fewest by far. I went to the CMPD patrol map to get an idea as to why crime in that area was so low, and I found that Airport exclusively covers the CLT airport, and not the surrounding areas. As for larger areas in CMPD patrol, Independence and South divisions were the locations with the least number of incident reports.
Areas with the highest number of incident reports were University City and Steele Creek, both charting very similarly in terms of numbers of reports each year.
This graph proved interesting as it further supported the idea that Covid did cause a reduced number of reported incidents, as 2020 saw a decline within all divisions.

I became interested in seeing how much incident reports changed annually. I created a dataframe to display the yearly changes using Pandas that would calculate the differences in the number of reports between each year. I also created a line chart using MatPlotLib, Pandas, and Colormap from MatPlotLib. Colormap was new to me, but I was searching for a way to make the visualization clearer to understand by giving each division their own color in the displayed graph. This graph also displayed very well the decline in reports in 2020 from 2019 and the mostly gradual rise again in 2021.