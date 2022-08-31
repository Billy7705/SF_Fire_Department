# SF_Fire_Department

In this project I worked with three of my classmates: [Arman Tavana](https://github.com/armantavanaa), [Arman Hashemizadeh](https://github.com/ahashemiz), [Neset Aydin](https://github.com/nesayd). Our goal was to map out San Francisco's fire department response time against different factors (budget, neighborhood, etc) in order for us to see what factors are important.

We used pyspark to be able to query information, perform data fusion, and create dataframes and graphs (see the graphs folder) from this data set that had over 5.5 million rows and 34 columns.

The process of this project:

We first put the data up on aws s3 buckets and used spark to read them in.
We found another dataset on funding of deparments in SF to merge in with our main dataset for us to explore the possibility of funding being an important factor for the repsonse time of the fire department.
We then used pyspark to preporcess our data and make sure is all ready for us to create data frames and graphs.
We then used spark to create spark dataframes and then by using spark dataframes we were able to create graphs to visualize average response time against year, budget, unit type, and by neighborhood.
