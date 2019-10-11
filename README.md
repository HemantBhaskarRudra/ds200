1. SCATTER PLOT:

	1.1 python file: scatter.py

	1.2 Data Source: https://data.gov.in/resources/monthly-seasonal-and-annual-max-temp-series-1901-2017-0

	1.3 Operating Instructions: The scatter.py file accepts data_source_filename from command line arguments. 
		So, in terminal type : 

		python3 scatter.py <data_source_filenme> , ie.,

		python3 scatter.py Max_Temp_IMD_2017.csv

	1.4 Plot : Scatter_Plot.png

	1.5 Plot Observations: The downloaded data file 'Max_Temp_IMD_2017.csv' from Data Source gives the maximum temperature for months January to December from year 1901 to 2017. The months were grouped on the basis of seasons they fall in. From wikipedia ( and India Meteorological Department (IMD) ) information for Climate of India (https://en.wikipedia.org/wiki/Climate_of_India), I have grouped the months 'December, January and February' for Winter season, 'March, April, and May' for Summer season, 'June, July, August and September' for Monsoon Season, and 'October and Novemeber' for Autum season. I have taken the average of maximum temperature of each constituting months within a season to determine the season's 'average maximum temperature'. For the value of annual 'average maximum temperture' I have taken the average of maximum temperature of all the months within that year. From the plot scatter_plot.png, the x-axis shows the 'year' and y-axis shows the value of 'average maximum temperature' seasonwise and annual for a given year. From the plot, it can be seen that the 'avearge maximum temperature' has increased annually from year 1901 to 2017 in INDIA. For Winter season the 'average maximum temperature' was less than 24 degrees for year 1901 and around, while for year around 2017 the 'average maximum temperature' can be seen to be approx 26 degrees. For Summer season also the 'average maximum temperature' was approx 30 to 32 degrees for year 1901 and around, while for year 2017 and around the 'average maximum temperature' can be seen to be approx 32 to 34 degrees. Similarly for the Autum and Monsoon season an increase in temperature from 1901 to 2017 can be easily seen from the plot. Hence a steady increase in temperature per season and annually is witnessed in INDIA from year 1901 to 2017.	This effect is mainly due to increasing deforestation and global warming. The effect of global warming in incrementing temperature of INDIA could be easily seen from the plots. The global warming are results of human emissions of greenhouse gases. Strict steps needs to be taken against incresing global warming like improving afforestation rate, controlling pollution and population, less usage of devices which emits greenhouse gases, etc.
