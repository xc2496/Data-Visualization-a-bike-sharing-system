# Data-Visualization-a-bike-sharing-system
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

Note that this dataset will require some data wrangling in order to make it tidy for analysis. There are multiple cities covered by the linked system, and multiple data files will need to be joined together if a full year’s coverage is desired. Resource link: https://s3.amazonaws.com/fordgobike-data/index.html
What is the structure of your dataset?
The dataset includes:

Bike IDs
How long was the bike rent for, in seconds
The information about end station ID, latitude, longitude and name.
The memeber's date of birth and gender
The information about start station ID, latitude, longitude and name.
The users' type as subscripted or not
There are 2252058 rows and 15 columns of the dataset

What is/are the main feature(s) of interest in your dataset?
I'm most interested in figuring out the usage of bike in different user groups, such as different genders or ages. For example, users in different genders may gave different usage bahavior, and users in differnt ages may also have different usage behvaior. The usage behavior can be the duration of using bike, distances and subscribe or not. I am also intereted in when are most trips taken in terms of day of the week and month of the year?

What features in the dataset do you think will help support your investigation into your feature(s) of interest?
I assume the genders do not have much differences in usage bahaviors. I also assume people in different user types have different usage bahaviors.

References:

#https://stackoverflow.com/questions/36519086/how-to-get-rid-of-unnamed-0-column-in-a-pandas-dataframe

#https://github.com/geopandas/geopandas/issues/1166

#https://geodata.lib.berkeley.edu/catalog/ark28722-s7hs4j

#https://towardsdatascience.com/geopandas-101-plot-any-data-with-a-latitude-and-longitude-on-a-map-98e01944b972

#https://geopandas.org/projections.html
