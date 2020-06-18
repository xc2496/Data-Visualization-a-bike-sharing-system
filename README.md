# Data-Visualization-a-bike-sharing-system
## by Xiaowen Chen
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

Note that this dataset will require some data wrangling in order to make it tidy for analysis. There are multiple cities covered by the linked system, and multiple data files will need to be joined together if a full year’s coverage is desired. Resource link: https://s3.amazonaws.com/fordgobike-data/index.html
## What is the structure of your dataset?
### The dataset includes:

##### Bike IDs
###### How long was the bike rent for, in seconds
###### The information about end station ID, latitude, longitude and name.
###### The memeber's date of birth and gender
###### The information about start station ID, latitude, longitude and name.
###### The users' type as subscripted or not
###### There are 2252058 rows and 15 columns of the dataset

## What is/are the main feature(s) of interest in your dataset?
I'm most interested in figuring out the usage of bike in different user groups, such as different genders or ages. For example, users in different genders may gave different usage bahavior, and users in differnt ages may also have different usage behvaior. The usage behavior can be the duration of using bike, distances and subscribe or not. I am also intereted in when are most trips taken in terms of day of the week and month of the year?

## What features in the dataset do you think will help support your investigation into your feature(s) of interest?
I assume the genders do not have much differences in usage bahaviors. I also assume people in different user types have different usage bahaviors.

## Discuss the distribution(s) of your variable(s) of interest. Were there any unusual points? Did you need to perform any transformations?
I cleaned the data before doing the plot. So in general, the plots look good and reasonable. Some details need to be changed. For the distrubution of distance in miles, few users had a greater than 30 miles riding. They look unusual. I may set the cut point in this situation.

## Of the features you investigated, were there any unusual distributions? Did you perform any operations on the data to tidy, adjust, or change the form of the data? If so, why did you do this?
For the age variable, some ages are too large, such as 139. This is definetly unreal age. few ages are greater than 100, so I dropped the users with age greater than 100 for a better visualization and analysis.

## Talk about some of the relationships you observed in this part of the investigation. How did the feature(s) of interest vary with other features in the dataset?
There isn't any obvious diffrences between genders in weekly usage and monthly usage. Females have a greater mean on the duration of usage than males. There is not an obvious difference between genders in distances.

## Did you observe any interesting relationships between the other features (not the main feature(s) of interest)?
In addition, in monthly usage, the distribution in customers and subscribers is slightly different. The most popular usage month for customers is October. The most popular month for subscribers is also October.

## Talk about some of the relationships you observed in this part of the investigation. Were there features that strengthened each other in terms of looking at your feature(s) of interest?
The multivariate charts helped to confirm some previous observations. Gender is not an obvious variable to determine the differences. The usage behaviors between genders are extremely similar.

## Were there any interesting or surprising interactions between features?
The customers prefer to use the Bikeshare on weekends, and the subscribers use the service on Monday-Friday, the most. This was not influenced by gender. Most subscribed users are using bikes on the Tuesdays in October and most customers are using bikes on the Saturdays on September. In both groups, people are using bikes fewer during winter seasons.
## References:

https://stackoverflow.com/questions/36519086/how-to-get-rid-of-unnamed-0-column-in-a-pandas-dataframe

https://github.com/geopandas/geopandas/issues/1166

https://geodata.lib.berkeley.edu/catalog/ark28722-s7hs4j

https://towardsdatascience.com/geopandas-101-plot-any-data-with-a-latitude-and-longitude-on-a-map-98e01944b972

https://geopandas.org/projections.html
