# surfs_up
## Overview of the analysis

I would like to relocate to Oahu in Hawaii and open a Surf n’ Shake shop serving surfboards and ice cream to locals, and tourists.  However, I don’t have enough money to get started, I have an investor who would like to back up my business venture, but he has asked me to investigate more about the island’s weather to make sure there are no surprises which may hamper the business.<br/>
The investor has provided me with Oahu’s weather dataset. I will use my expertise with SQLite (i.e., A version of SQL that lives on computer or phone, so is smaller, faster and doesn't have users), and SQLAlchemy (i.e., A query tool designed for SQLite and the integration of statistical analysis with data frame analysis) to analyze this dataset.<br/>
The analysis results will assist me and the financier to refine our venture and avert any shortcoming in our investment due to weather.

## Results

### *	Summary Statistics for June

The month of June had a maximum, a minimum, and a mean of 85.00-, 64.00-, and 74.94-degree Fahrenheit respectively. The temperatures appear to be normally distributed and the standard deviation is about 3.26.<br/>
#### Table 1: June Temperatures Statistics <br/>
![June Statistics](https://user-images.githubusercontent.com/34750363/155005569-eae7fe8f-6942-45aa-b94b-e44eacdd1f9c.png) <br/>
#### Graph 1: June Temperatures Statistics <br/>
![June Bar-graph](https://user-images.githubusercontent.com/34750363/155005620-875d984b-f4cc-4ace-9ca1-1b3b1c894b8c.png)

### *	Summary Statistics for December

The month of December had a maximum, a minimum, and a mean of 83.00-, 56.00-, and 71.04-degree Fahrenheit respectively. The temperatures appear to be normally distributed and the standard deviation is about 3.75.<br>
#### Table 2: December Temperatures Statistics <br/>
![December Statistics](https://user-images.githubusercontent.com/34750363/155005866-531ee6e0-af1f-476a-812f-1e844453d25c.png) <br/>
#### Graph 2: December Temperatures Statistics <br/>
![December Bar-graph](https://user-images.githubusercontent.com/34750363/155005891-0f26f8ad-6cdd-4d38-ac9d-1a525210b937.png)

### *	Summary Statistics: June vs December Temperatures

The month of June appeared to be about 3 degrees warmer than December. Also, June had a low standard deviation, thus, the temperature data points were closer to the mean compared to December in which the temperature data points were further away from the mean.<br/>
#### Table 3: June vs December Temperatures Statistics <br/>
![Summary Statistics - June vs December Temperatures](https://user-images.githubusercontent.com/34750363/155006221-323abc38-ee7e-45c7-9ee0-a9a1c8e4e25c.png)

## Summary

The Oahu’s weather data analysis revealed that June was warmer than December, and its data was less unstable due to its smaller standard deviation (i.e., smaller variance). Therefore, we concluded that the business performance would be stronger during the month of June, because most people tend to crave for ice cream during hot weather. In addition, June would be more attractive to locals and tourists that are interested in surfing due to its data’s smaller variance which translate into a less volatile weather condition. Hence, most likely high demand for surfboards at the Surf n’ Shake shop.

## Limitations and Suggestions

Even though, the mean and standard deviation for June and December are different by just comparing the numbers. We could run specific statistical analyses to make sure that they are statistically different. For instance, we could run a Z-test and a T-test to compare their distribution and means respectively.
Also, it wouldn’t hurt anything to analyze data for all the year’s months, opening more insights about the weather conditions on the island.

