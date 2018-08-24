
Summary

This project was based on some data available at Kaggle and it is about the world ranking for universities. We have 4 different charts to understand a little bit about the best universities on earth and what differentiate them. It will interesting to notice how well known top universities as Harvard, California Technology Institute and Oxford behave. 

Design

The data comes from Kaggle [1] and because the data included so many universities I decided to use Excel to do some cleaning. As I was interest only at top universities removed the others and used only the top 20 universities without blank spaces in the attributes and correct attributes characters values.

After this first cleanig I selected some universities of interest as Harvard, Caltec and Oxford to have a deeper analysis, as they are well known and ended up in interesing positions in 2016. Caltec in the first place folowed by Oxford and the big decrease of Harvard dropping from 1st (2011) to 6th (2016). 

With this information in hand an interesting question arises, why Harvard is no more the 1st University, what Oxford and Caltec did that Harvard missed?  

To analyse and explain this I decided to use dimple.js because it is build on top of d3 and it is very easy to use and has many tutorials and examples available.

I considered using multiple charts as scatterplots, line charts, bubble charts, bar chart and many others. But I ended up chosing a mix of bubble chart and line chart. Specifically buble chart is a good choice because we can have a 3d visualization without decreasing the readability of the plot. This is able because we can set the x, y, color, shape of the plots and some animation available at dimple.js. The line chart is a good complementary for the proposed analysis because it helps to identify trends.



References

[1] https://www.kaggle.com/mylesoneill/world-university-rankings
[2] http://dimplejs.org/
.
