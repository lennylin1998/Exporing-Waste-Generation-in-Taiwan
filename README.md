# Exporing-Waste-Generation-in-Taiwan
## Overview and objective
This is an exploratory analysis on waste generation in Taiwan. In this project, I aim to find out wich county in Taiwan has done well on waste control, and on increasing recycling rate. The tool will be python. Pandas and plotly are two main libraries used. Here I include data source, glossary, outline and some graph. Make sure to check them out before jumping into the project! Thank you for reading, and comments are always welcome! 
## Source and reference
* Datasets: [Environmental Protection Administration Executive Yuan, ROC Taiwan](https://stat.epa.gov.tw/)
* References: [Plotly Documentation](https://plotly.com/python/)
## Glossary
|Column Name|Explanation|
|---|---|
|year|year|
|month|month|
|county|county name|
|waste|total waste: trash + recycling + food waste|
|trash|unrecyclable waste|
|recycling_gen|waste that are recyclable, but not including food waste|
|food waste_gen|waste used to be edible, leftover|
|waste/d/p|total waste divided by "days in that month" and "population of the county"|
|food_waste/d/p|food waste divided by "days in that month" and "population of the county"|
|recycling_rate|(recycling + food waste)/waste|
## Outline
1. Plot the waste over time to inspect trend.
2. Find the relationship between waste and recycling rate
3. Calculation to determine performance of each county and display the result
4. Subsidiary analysis
## Analysis highlight (graph)
![g1](https://github.com/lennylin1998/Exporing-Waste-Generation-in-Taiwan/blob/main/graph/newplot.png)
![g2](https://github.com/lennylin1998/Exporing-Waste-Generation-in-Taiwan/blob/main/graph/newplot%20(1).png)
![g3](https://github.com/lennylin1998/Exporing-Waste-Generation-in-Taiwan/blob/main/graph/newplot%20(2).png)
## Update
* First Upload: Jul. 17, 2021
