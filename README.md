# MUSIC AND STOCK EXPLORATORY DATA ANALYSIS
Project 1 for Group 2: Jonathan Lilley, Ama Tutuwaa, Fiona Blackmon-Burns, Erika Tan, Andrew Herr.

## PROJECT BLURB
The goal of this project was to explore the potential relationship between people's listening trends/ preferences and stock market returns. Using data from the Spotify API's Daily Top 100's list and historical stock market data like NASDAQ, VIX, and SWBI, the team analyzed whether there was any correlation between the two variables. Our findings are summarised below.

## PART I - While major catastrophic events have an impact on stock performances, is there an extended effect on Music preferences?

The **hypothesis** was that major catastrophic events (i.e. a mass shooting) would not only impact the stock performance of gun/ammo manufactures, but it would also **correlate with changes in people’s music preferences**. Although Smith and Wesson’s (SWBI) stock price reacted to mass shootings and the adoption/proposal of stricter gun laws, people’s music preferences weren’t quite the same. **Neither music characteristics of the songs in Spotify’s Daily Top 100 nor any of the genres having more songs in Spotify’s Daily Top 100 had a strong correlation with changes in SWBI’s stock price**. For music genre, the strongest correlation (0.63) was between the total number of unique pop songs in Spotify’s Daily Top 100 for the month compared to SWBI’s average closing price. The correlation for the music characteristics was even weaker, but the strongest correlation for the group (0.53) was between the average valence score for all songs in the Top 100 for the month compared to the average closing price.



## PART II - 



## PART III - Music Influences Stock Interactions?
Using the VIX Stock and Spotify Daily Top 100, we also decided to do a reversed analyis to see if a possible correlation between Music listening Trends and Stock Market Interactions would be when looking at stock market returns as the reactionary variable.

Our question was: **Can Music on Spotify Shed light on Stock Market Returns?**

**Hypothesis**: The type of music people listen to at any given moment is a reflection of their mood and influences how they choose to use their money
A key assumption had to be made for this EDA to have a firm logical ground.

**Assumption**: People listen to music that reflects the mood they are currently experienceing, rather than listening to music to change their mood.
To set the Stock market return as the **reactionary variable** we had to lag it by 3 days in conjuction with the spotify data to be able to map out the feedback.

The graph below shows the final result of this subset of our eploratory data analysis
![Graph Mustic to Stock analysis](https://user-images.githubusercontent.com/114604829/219490986-69dee63b-e143-4458-980c-db57946d3a6f.png)

The double y-axis graph above shows the final result of our analysis and **indicates a positive correlation between Music Valence and Stock Closing prices** on the y-axes and date on the x-axis.

The left y-axis represents the Music Valence score, which is a measure of the positivity or negativity of a song, and the right y-axis represents the Stock Closing price, which is the final price of a stock at the end of a trading day. The x-axis represents the date.

The line plots in the graph show a mirroring trend for both the Music Valence score and the Stock Closing price. As in upward shifts in the Music Valence are often replicated (not to the same degree/slope) with upward trends in the Closing price and the same applies for downward shifts. This suggests that there may be a positive correlation between the two variables over time.

The double y-axis graph is an effective way to visually represent the relationship between two variables that have different units of measurement, as it allows you to plot them on the same graph and easily compare the trends. However, it is important to note that the use of a double y-axis can sometimes be misleading, as it can exaggerate the correlation between the two variables. It is also important to note that correlation does not necessarily imply causation, and further research is needed to establish whether there is a causal relationship between Music Valence and Stock Closing prices. However, the positive correlation shown in this graph provides initial evidence that there may be some relationship between the two variables.


## PART IV - 

## CONCLUSION
