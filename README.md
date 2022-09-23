# PyBer_Analysis

## Overview
This purpose of this project is to summarize the differences in data by city type for a ride share company called PyBer, and how those differences can be used by decision-makers at PyBer.

## Results
After merging the data sets and creating a summary dataframe by city type, the data finds:
- There are 13 times more rides in urban cities, compared to rural cities (1,625 vs 125 rides).
- The average fare per ride is 1.4 times less and average fare per driver is 3.4 times less in urban cities, compared to rural cities ($24.53 vs $34.62 and $16.57 vs $55.49).
- The total fares in urban cities are 9 times higher compared to rural cities, and 2 times higher compared to suburban cities. ($39,854.38 vs $4,327.93).

![table summary of rideshare data](analysis/table_summary.png "table summary of rideshare data")

The multiple line plot of the total weekly fares for each city type supports the data. The Urban line is higher than the Suburban or Rural lines, indicating higher fares in Urban areas.

![multiple-line plot](analysis/PyBer_fare_summary.png "multiple-line plot")

## Summary
- The data suggests that while urban cities make the most in total fares, there is an abundance of drivers (2,405) compared to the amount of rides (1,625). This leaves some drivers with no rides. Reducing the number of drivers is suggested. Reducing the number of drivers will also increase the average fare per driver in the region.

- Additional analysis may be done on ride duration and miles driven. With this additional data, average fare per minute or mile may be calculated and compared. This information can be used to adjust fares efficiently between city types.
