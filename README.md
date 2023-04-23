Final Project - COVID-19 and its effect on the stock market (100 Marks)
You have been tasked with creating some visualizations and reporting on the effect of COVID-19 on the stock market.  You will use all of the concepts and skills you have learned so far in this course.  You may have a group of up to 3 participants to produce the solution to the final project.
Steps:
1)	Set up a Git repository to allow you to collaborate on the Python solution
2)	Read the daily confirmed cases and deaths into two dataframes can be found at this github page:
a)	confirmed_cases_url = "https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv"
b)	deaths_url = "https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv"
3)	Use pandas to create a dataframe that aggregates and sums both confirmed cases and deaths on a global level
4)	Research a stock for each below that reflects the following industries (it will be used in the next step):
a)	Overall American Market
b)	Overall Canadian Market
c)	Travel sector
d)	The Real Estate sector
e)	Precious metals (Gold, Silver, Platinum, etc)
5)	Use AlphaVantage (the stock API used earlier in the course) to get the daily high and low prices for your selected stocks
6)	Append that info to the data frame created in step 3)
7)	Create an appropriate graph detailing your info - explain why you chose the graphs you did, use matplotlib

