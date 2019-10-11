1. SCATTER PLOT:

	1.1 python file: scatter.py

	1.2 Data Source: https://data.gov.in/resources/monthly-seasonal-and-annual-max-temp-series-1901-2017-0

	1.3 Operating Instructions: The scatter.py file accepts data_source_filename from command line arguments. 
		So, in terminal type : 

		python3 scatter.py <data_source_filenme> , ie.,

		python3 scatter.py Max_Temp_IMD_2017.csv

	1.4 Plot: Scatter_Plot.png

	1.5 Plot Observations: The downloaded data file 'Max_Temp_IMD_2017.csv' from Data Source [4] gives the maximum temperature for months from January to December for the year 1901 to 2017. The months were grouped based on the seasons they fall in. From Wikipedia 'Climate of India' [1] information and India Meteorological Department (IMD) [2,3] information, I have grouped the months 'December, January and February' for Winter season, 'March, April, and May' for Summer season, 'June, July, August and September' for Monsoon Season, and 'October and November' for Autumn season. I have taken the average of the maximum temperature of each constituting months within a season to determine the season's 'average maximum temperature'. For the value of annual 'average maximum temperature,' I have taken the average of the maximum temperature of all the months within that year. From the plot Scatter_Plot.png, the x-axis shows the 'year' and the y-axis shows the value of 'average maximum temperature' season-wise and annual for a given year. From the plot, it can be seen that the 'average maximum temperature' has increased annually from the year 1901 to 2017 in INDIA. For Winter season the 'average maximum temperature' was less than 24 degrees for the year 1901 and around, while for year 2017 and around the 'average maximum temperature' can be seen to be approx 26 degrees. For the Summer season also the 'average maximum temperature' was approx 30 to 32 degrees for the year 1901 and around, while for the year 2017 and around the 'average maximum temperature' can be seen to be approx 32 to 34 degrees. Similarly, for the Autumn and Monsoon season, an increase in temperature from 1901 to 2017 can be easily seen from the plot. Hence a steady increase in temperature per season and annually is witnessed in INDIA from the year 1901 to 2017. This effect is mainly due to increasing deforestation and global warming. The effect of global warming in the incrementing temperature of INDIA could be easily seen from the plots. Global warming [5] is the result of human emissions of greenhouse gases. Strict steps need to be taken against increasing global warming like improving afforestation rate, controlling pollution and population, less usage of devices that emit greenhouse gases, etc.

	1.5 References:

		1. Wikipedia: Climate of India 
		   https://en.wikipedia.org/wiki/Climate_of_India

		2. India Meteorological Department (IMD)
		   http://www.imd.gov.in/Welcome%20To%20IMD/Welcome.php

		3. India Meteorological Department (IMD) : Frequently Asked Questions (FAQ)
		   http://imd.gov.in/section/nhac/wxfaq.pdf

		4. Monthly, Seasonal and Annual Max Temp Series from 1901 to 2017
		   https://data.gov.in/resources/monthly-seasonal-and-annual-max-temp-series-1901-2017-0

		5. Wikipedia: Effects of global warming
		   https://en.wikipedia.org/wiki/Effects_of_global_warming


2. BAR PLOT:
	
	2.1 python file: bar.py

	2.2 Data Source: https://data.gov.in/resources/variety-wise-daily-market-prices-apple-2019

	2.3 Operating Instructions: The bar.py file accepts data_source_filename from command line arguments. 
		So, in terminal type : 

		python3 bar.py <data_source_filenme> , ie.,

		python3 bar.py Apple_2019.csv

	2.4 Plot: Bar_Plot.png

	2.5 Plot Observations: The downloaded data file 'Apple_2019.csv' from Data Source [4] gives 



