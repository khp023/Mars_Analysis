# Mars_Analysis

## Overview and Techniques

In the process of analyzing various statistics regarding the planet Mars, web-scraping techniques through Python were utilized. The analysis shown was completed through using Splinter and BeautifulSoup on Python. The source websites used were [Mars Planet Science](https://redplanetscience.com) and the [Mission to Mars](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) dataset. 

## Charts

The following was obtained after successfully scraping the data table and processing through Pandas. 

Figure 1. Average Low Temperatures (°C) by Month
![lowtemp_by_month](/images/lowtemp_by_month.png)

Figure 2. Average Pressures by Month
![pressure_by_month](/images/pressure_by_month.png)

Figure 3. Lowest Temperature in a Day vs Each Terrestrial Day 
![days_in_year](/images/days_in_year.png)

## Analysis

We find through this analysis that there were 12 determined months in a Martian year. These are reflected Figures 1 and 2. The Curiosity rover was found to be present on the planet for 1867 martian days. 

According to Figure 1, the coldest month is the third, with the warmest being the eighth. Figure 2 shows that the month with the lowest atmospheric temperature is the sixth, with the highest pressures seen in the ninth month. 

In regard to the numnber of Earth days in a Martian year, we can determine this by looking further at Figure 3. Similar to seasonal patterns, the peak to peak difference in days results in ~650-700 days. Per NASA, we confirm that this is a reliable analysis method-  roughly 687 days. 

