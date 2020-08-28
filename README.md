## Exploring Weather Trends
### Overview
As we all know that global temperature is getting warmer as ever. In this project,the data set was given to me as part of the [Udacity](https://classroom.udacity.com/nanodegrees/nd002/parts/93426fc7-0e68-4957-b16b-9fde38776c26/modules/e8455c07-092a-4b76-ba12-018cb53d0526/lessons/d551938c-d004-4801-a269-4b8dd784cc3b/concepts/530f21c0-2f37-4390-aaab-3ce440e56d80) program. The average temperature of global weather trends file is to be extracted from the `SQL` database. I extract the data and export its into two files `global weather.csv`and `local weather csv`. The global weather.csv consists of 2 columns, `year` and `avg_temp` which recorded the average temperage each years in Celsius. The local weather.csv contain 4 columns, `year`, `city`, `country`, `avg_temp`, which also recorded the average temperature in Celsius of San Jose which also known as `Silicon Valley`.

### Objective Overview
- Exacting data from the dataset by using SQL
- Using pandas for data manipulation
- Using matplotlib for data visualization
- Making observation by analyzing the visualization 

## SQL query used to extract the data from

### Query for extracting data from local weather trend dataframe.
SELECT * FROM city_data
WHERE city='San Jose'

### Query for extracting data from global weather trend dataframe.
SELECT * FROM global_data

### References
- [Sources code for the output_toggle.tpl file](https://github.com/damianavila/blog/blob/master/posts/hide-the-input-cells-from-your-ipython-slides.ipynb)
- [Udacity](https://www.udacity.com)
