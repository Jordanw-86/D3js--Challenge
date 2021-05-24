 # D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## The task at hand

Welcome to the newsroom! I've just accepted a data visualization position for a major metro paper. I am tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand your findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on me to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the assignment is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml), The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Tools for this task

1. Used  `D3-Library`

2. **html** and **Javascript** 

3. Inside your local **git repository**

4. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.


### 1. Core Assignment: D3 Dabbler (BASIC STATIC CHART)

![4-scatter](Images/scatterchart.png)

**CHALLENGE COMPLETED!!**

* You need to create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

* Using the D3 techniques create a scatter plot that represents each state with circle elements. I code this graphic in the `app.js` file, which have the Basic Chart coding. Pull in the data from `data.csv` by using the `d3.csv` function. 

* Included state abbreviations in the circles.

* Create and situate your axes and labels to the left and bottom of the chart.

* Used `python -m http.server` to run the visualization. This hosted the page at `localhost:8000` in my web browser.

* Used [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how to implement tooltips with d3-tip.

