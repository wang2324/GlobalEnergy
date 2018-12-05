# Technical Report
## Abstract
Every day, our species chews its way through more than a million terajoules of energy. That’s roughly equivalent to what 
we would use if all 7.5 billion of us boiled 70 kettles of water an hour around the clock. Or 3,000 times the daily output of 
Palo Verde nuclear power station in Arizona – one of the world’s largest – running at full capacity. With the global population
swelling and industrialization on the rise in developing nations, humanity’s hunger for energy has reached unprecedented levels.
Therefore, it could be a good approach that visually present our nowadays’ energy production and consumption condition to help 
people better learn about our current condition.

## Objectives
1)	Realize insights about energy issues with data visualization.
2)	Make a use of various tools and advanced techniques to create an excellent visualization which is able to communicate information clearly and efficiently to the end users.
3)	Display the final project on a dynamic website which can be easily navigated and understood.

## Functional requirements
1)	Since sectional dynamic web site is using Google Spreadsheet as a database, the related dataset has been populated. Thus, this Google Spreadsheet’s URL can be successfully queried in the code. 
2)	The main tools used to create professional charts in this project are Google API and eChart API. The Google Chart library and eChart library are required to be loaded in the <head> of the web page. The eChart library has been downloaded to the local and used as <script src="echarts.js"></script>.
3)	The style of home page is using w3.CSS website template, and the library is loaded as:
 <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  
## System Architecture and Description
The final presented dynamic web site is consist of four main subpages which are: Home, Energy Analysis, CO2 Emission and Contact. Except Energy Analysis page, the other three inherit the similar web design but with different content. All of them have a side navigation on the left-hand side with a different icon for each menu and the black background on the right. When the users head to the Energy Analysis page, there will be a responsive navigation containing Home, CO2 Emission and Contact button which can bring them back to the main page. While under the top navigation, there are also five hover tabs corresponding to five different energy sources. When mouse over the navigation links, it will change their colors. The majority of important charts are displayed here.

## Development platforms
All the code is edited and complied on Sublime Text which is a proprietary cross-platform source code editor and natively supports many programming languages. The languages used in this project includes HTML5, CSS and JavaScript. 

## Proposed visualizations
Various Interactive charts are used in this project including stacked column chart, bar chart, donut chart, normal pie chart, nested pie chart, bubble chart, treemap, step chart, stacked line chart, column chart with polar coordinate, geomap and nightingale's rose diagram. In addition, there’s 3D global which will be auto rotating when the CO2 Emission page opened. Different chart type is used depending on different data type and which characteristics of data would like to be highlighted. 

## Experimental analysis and conclusions
In this project, the dynamic web site was constructed first in order to make it clear that what information and charts need to be provided in each section. W3schools website provided many attractive web design templates and Awwwards website also provided collections of excellent web design works. Exploring and learning from others’ ideas was pretty helpful to give me some inspirations on how to start the project. When working on the data visualization, initially all the creation of charts was based on Google API. However, later eChart Library was largely used instead because I found it provided more diverse chart types and was easily to customize. Besides, it offers more interactive effects, for example the users are able to click the data legends to choose which parts of data to display. 
There are a couple of information can be obtained from displayed charts. The total energy consuming is increasing year by year, in which Asia and North America is taking up the majority. The specific consumption and production varies according to countries and energy sources including natural gas, electricity oil products, coal and renewables. 


  
