# WeatherDataReader
How to import weather station data using SSIS

In this project I have imported my weather station data to SQL Server using SSIS. The example data is from 2015 with some 240000+ entries in separate files.

For further reporting applications I decided to combine date and time fields to a single datetime field, thus the script element.

For a quick reviews, just look at the pictures.

Data Disclaimer: My weather station is not at the optimal place so especially rain fall rate does not necessary tell the truth. Also, my weathger station does not have a solar sensor so those values are zeros, however I wanted to include them if you have any use for them.
