# How-AirBnB-Fared-in-Seattle-and-Boston-in-2016-2017

Motivation:

This work is an assessment of the tourism business of AirBnB in the cities of Seattle and Boston USA 2016-2017, through data analysis. The key motivating factor is the volume of home accommodations listed on AirBnB plaforms. The analyst therefore decided to analyze the data to find out more about what goes on in this business in these two chosen cities.

Repository Files: 

This work used python programs to analyze the data of both cities (Seattle and Boston).
In this repository, there are the following files:
1. boston_airbnb: This is the python program used to analyze the Boston data as compiled by AirBnB. It was created with Jupyter notebook.
2. seattle_airbnb: This is the python program used to analyze the Seattle data as compiled by AirBnB. It was also created with Jupyter notebook.
3. seattle_boston: This is a zip file of the datasets of both cities. Inside it are files boston_data and seattle_data, both of which are csv files.

Libraries Used:

The python libraries used in this work are numpy and pandas.
With pandas, visualization of the files shows that they are identical in structure, with 4 columns each, namely 'listing_id', 'date', 'available' and 'price'.

Analysis and Findings: 

In the datasets given, there were 1,393,570 listings in Seattle with 459,028 missing price values (that is, about 33% proportion of missing values), while in Boston, there were 1,308,890 listings with 665,853 missing price values (that is, about 51% proportion of missing values). Missing values occured only in the price column, meaning that there were no accommodations for the existing listing ids. It was therefore a good idea to drop all the records associated with the missing prices.

In Seattle, a total of 3,723 different listing ids featured, while 2,906 featured in Boston. However, the listing ids with the highest frequency of feature appeared 365 times for each of the cities. For Seattle, there were 678 of such listing ids, while Boston had 103. Furthermore, the listing ids with the least frequency featured only once for both cities. In Seattle, such ids were 7, while in Boston, there were 26.

About listing dates, a total of 365 different dates featured over the period. In Seattle the most frequently featured date was 2017-01-01. It featured for 2,922 times. Similarly, in Boston the most frequently featured date was 2016-12-04 and it featured for 2,207 times. Conversely, the least frequently featured date in Seattle was 2016-01-04 and it featured for 1,735 times, while that of Boston was 2016-09-06 and it featured for 570 times. These frequencies denote the number of accommodations listed in those dates.

In terms of accommodation prices, 669 different prices featured for the various Seattle accommodations. In Boston, the range was rather wider – 1,246 different price tags. Coincidentally, the mode of price tag for accommodations for both cities was $150.00. For Seattle accommodations, its frequency was 36,646 times, while its frequency was 20,752 times in Boston. In both cities again, the price tags with the lowest frequency featured only once. In Seattle, there were 66 of such different price tags, while there were 225 of such in Boston.

More About the Analyses:

In the programs used to analyze the data, there are many functions one can use to further explore and study the data. Most of them are basically meant to help in visualizing some of the feature variables of the data. For instance, some listing ids, dates and prices featured for several times. In order to visualize their distributions in the data, it is easier to take the long lists chunck by chunk. This is made possible by some of the functions. Some other functions display the feature variables side by side for possible comparison. Although there are no definite correlations among the features, it is still a good idea to view them. Moreover, contributors are welcome to make their inputs to further improve the functionalities of the programs.

Summary: 

Looking at the two cities – Seattle and Boston – it is safe to say that Seattle is more commercial than Boston. This is evident in the fewer number of unavailable listing ids, as well as the higher number of maximum accommodation listings per day in Seattle. What this means is that more people list their homes for tourist accommodation in Seattle than in Boston. However, there are more price options in Boston than in Seattle. While Seattle had 669 different price options, Boston had 1,246 options. It will be a good idea to increase the price options of Seattle accommodations to create more possibilities of patronage from members of the public. Meanwhile, it seems that most tourist customers were comfortable with the price of $150.00 as evident in both cities.

Conclusion: 

By the foregoing, it can be deduced that in AirBnB, one listing id can be used repeatedly to list different accommodations. It can also be inferred that hosts can have their accommodations listed on AirBnB platform on any day of the year, including Christmas day. This means that AirBnB works all year round. Furthermore, as many accommodations as possible can be listed in a day, with different price tags according to peculiar factors considered by AirBnB. The implication is that there is no limit to the number of accommodations that can be listed in one day.

Acknowledgement:

I sincerely appreciate AirBnB for allowing its data to be used for this exercise. I also thank Udacity team for her tutorials. They helped me a lot in writing the programs of this project. Next is Mosh Hamedani and Daniel Chen whose videos also helped me in the coding. I salute all the people behind this help and say, thank you.

References:
1. https://classroom.udacity.com/nanodegrees/nd025/parts/5b4ccaa7-bdcd-4ea3-9538-97673aa035c4/modules/12e3e314-fb99-47e1-967b-b6620e3cff34/lessons/1c9dcfa1-01ed-4302-858a-c14bd8173edc/concepts/ac7b8917-6765-46ec-a17a-6ebdd71d67a4
2. https://www.youtube.com/watch?v=iYie42M1ZyU&t=848s
3. https://codewithmosh.com/courses/417695/lectures/9219316
