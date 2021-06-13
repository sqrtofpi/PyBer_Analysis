# Ride-Sharing Analysis with Pandas and Matplotlib
Click here to view the Pandas file: [Ride-Sharing Analysis Program](https://github.com/sqrtofpi/PyBer_Analysis/blob/36d87fe5bc12424d89e8647375755cef2aacebb8/PyBer_Challenge.ipynb)

## Overview of the Analysis

Pyber (a ride-sharing company), whose CEO V. Isualize has given my colleague Omar and myself, Scott MacDonald, a new assignment to create a summary DataFrame using Pandas and Jupyter notebook of the company's ride-sharing data over nearly 4 months (Jan - April '19) by city type. In addition, we will be using Pandas and Matplotlib to create a multiple-line graph showing the total weekly fares for each city type. The objective of the analysis is to summarize how the data differs by city type and to provide three business recommendations to the CEO addressing any disparities amont the city types based on the analysis. 

## Results

DataFrame by city type:

![DataFrame of Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver by City Type:](../../../Module%201%20-%20Kickstarting%20with%20Excel/Module%201%20Challenge/Resources/DataFrame.png)

As we can see in the summary DataFrame, most of the fares were collected from urban cities while rural cities offered the most lucrative fares to the drivers despite having much fewer drivers servicing these rural cities. To further illustrate the effect we submit a graphical representation:

![PyBer Ride-Sharing Data (2019)](../../../Module%201%20-%20Kickstarting%20with%20Excel/Module%201%20Challenge/Resources/Fig1.png)

As the illustration confirms, although there are many more rides in the urban areas, likely due to population distribution, more money can be generated per ride in a rural city. With only 2.62% of driver availability in rural areas but the average ride offering an increase of 41.13% in revenue, it appears to be an opportunity worth further investigation.

Our analysis also yielded another illustration showing the relationship over this 4 month period during 2019 which the dataset was obtained:

![Total Fare by City Type](../../../Module%201%20-%20Kickstarting%20with%20Excel/Module%201%20Challenge/Resources/PyBer_fare_summary.png)

This illustration shows the relative stability of fares collected in each city type. There are minor fluctuations in the fare contribution to the company, but any conclusive reason for the fluctuations would be speculative without further data to understand what might explain the differences over time. For instance, were there special events happening in the urban area through late February to mid-March that could've contributed to the spikes and declines in revenue, maybe spikes on weekends due to special events in the city? Also the spike in all three city types in late February could have some correlation but the data doesn't include what that event could be. There is no cross-over amongst these three city types during this time-frame and from the chart we could anticipate that trend would continue with more data but that is speculation as there may be a cyclical or seasonal component to PyBer's business model.

## Summary

Upon completion of this analysis, Omar and myself recommend the three following actions:

First that we continue to monitor and increase the dataset. This analysis contains only 4 months of data and there may be a seasonal or cyclical component to the business cycle which should be studied more carefully as any changes to the business based upon a small sampling of the business cycle might have a detrimental affect on revenue. There should be a multi-year analysis to identify this business cycle and if needed sooner, it may be able to be obtained through benchmarking competitors if that data is obtainable.

Secondly, based upon the current dataset, we would recommend increasing the number of drivers in the rural cities. They generate more revenue and could easily increase PyBer's bottom line with redeployment of urban drivers to rural city settings. There is an abundance of urban drivers where competition with other ride-sharing company's is also a key consideration.

Lastly, based upon the current dataset, we feel there is an opportunity to gather additional information about the "reason for the ride" to better understand any improvements that can be made. In urban areas, there are many concerts, sporting events, etc. that typically do not occur in rural settings. In addition, urban city dwellers are less likely to have a vehicle of their own due to the proximity of everything they need being relatively close and the cost of storing and paying for parking a personally owned vehicle. There may also be less ride opportunities in rural city areas so understanding the reasons people are choosing PyBer's services is important to understand in context of the already obtained data.
