# Assignment 2: Data visualization #1 - Visualizing government debt
# Week 2
## Link to online portfolio: https://kkalaga.github.io/tswd/

### Source
> The data used for all the visuals below is called the "General Government Debt" dataset from "The Organization for Economic Co-operation and Development (OECD)". It contains debt to GDP ratio across different years and for different countries.
> According to OECD,
> ***"General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. It is a key indicator for the sustainability of government finance. Debt is calculated as the sum of the following liability categories (as applicable): currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable. Changes in government debt over time primarily reflect the impact of past government deficits."***

### Part 1: Working with web-based visualization tools and data

<iframe src="https://data.oecd.org/chart/65vM" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/65vM" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>

### Part 2: Working with Flourish
> Using Flourish to create a grid of lines chart similar to sparklines. This type of visulaization helps us to see the trends across various countries and through different years at the same time. The following chart shows the Debt-to-GDP ratio of each country from 1995 to 2019.

<div class="flourish-embed flourish-chart" data-src="visualisation/3740956" data-url="https://flo.uri.sh/visualisation/3740956/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

###### Heatmap with Flourish
> Using Flourish to create a heatmap of the Debt to GDP values to see hot spots (countries with very high ratios) and cold spots (countries with low ratios).

<div class="flourish-embed flourish-heatmap" data-src="visualisation/3758400" data-url="https://flo.uri.sh/visualisation/3758400/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

##### Comparing the three visuals above
> All the three above viuals have the same data set but they tell a slightly different story and cater to different target audience. The first bar graph and heatmap is used to see over all trends for all the countries together and they can easily help audience understand where is the general trends and where outliers lie. One of the main difference between the bar graph and heat map is that the bar graph can only tell us about one choosen year where as the heatmap can show trends throughout all the years. These trends through out the year can also be acheived using the second visual which is a grid of lines. But grid of lines has multiple plots one for each country and we can only see trend for one country through the years. This two dimensional type of trend functionality in heat map was the main factor for my choice for this dataset. 

> To summarize, the following are the focus points for each visual:
> 1. Bar chart: Trend across all the countries for a single year
> 2. Grid of lines: Trend across years for each country plotted on a separate plot
> 3. Heatmap: Trend across all the countries through all the years
