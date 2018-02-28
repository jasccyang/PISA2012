# Student Performance Based on Location

## Visualizations
Pre-Feedback: 2012PISA-Performance 
Final: 2012PISA-Performance3 

## Summary
This Tableau display examines student performance based on location. Two highlighters are available on the top right to visualize the data in terms of country OECD membership and top performing countries with student composite scores of greater than 1500. A scatter plot and bar plot were included to provide insights on student’s number of possessions, study time, and gender performance.

## Design
### Location
I chose map chart with color differentiation to show geographical location of top performing nations.
### > 1500
Bar chart to show a clear cut between countries performing above score of 1500.
### PossessionStudy
Scatter plot with shape and color differences for multivariant analysis. Using this plot, we can visualize each country’s OECD membership and score performance in relation to number of possessions and study time.
### GenderScore
Bar chart to see the score breakdown of each country based on gender. 
<br>
When designing a visualization for this data set, I wanted to include information about location and gender. This was difficult to display because not many features describe both gender and location. For example, the OECD membership feature is a useful detail for location, but does not apply to gender. In the Pre-feedback display, I focused on both gender and location equally. This made it difficult understand what the display was trying to convey. In the final version, I kept only location relevant labels in the legend and removed a graph regarding gender count.

## Files
Reducing File Size.ipynb: Jupyter file to resize and wrangle the data <br>
Pisa2012_1000th.csv: 1/1000 size of original PISA survey file <br>
PISA2012_processed.csv: cleaned up csv file with relevant columns
