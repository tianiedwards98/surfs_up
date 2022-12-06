# Surfs_Up

## Overview
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

## Results
-- In June we had a total count of 1700, mean of 74.9, min of 64.0 and max of 85.0

![DataFrame](https://github.com/tianiedwards98/surfs_up/blob/main/Images/June_temps.png?raw=true)

-- In December we had a total count of 1517, mean of 71.0, min of 56.0 and max of 83.0

![DataFrame](https://github.com/tianiedwards98/surfs_up/blob/main/Images/December_temps.png?raw=true)

-- Standard deviation is 3.25 in June and 3.75 in December -- making a .5 difference in the two different seasons

## Summary

From our data we can tell what our temperatures are but since there are other attributes to the weather such as precipitation it shows that we can run additional queries to let us know whether or not people can come and visit the shop. If we are able to gain more data for the area we can run even more queries! From there we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.
