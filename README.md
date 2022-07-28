# Belly_Button_Diversity
 
## Overview

In this assignment, I built an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

This assignment has three graded deliverables. The deliverables are as follows:

### 1. Deliverable 1
------
Using my knowledge of JavaScript, Plotly, and D3.js, I created a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage.

My code includes the following:

- Code is written to create the arrays when a sample is selected from the dropdown menu
- Code is written to create the trace object in the buildCharts() function, and it contains the following:
- The y values are the otu_ids in descending order
- The x values are the sample_values in descending order
- The hover text is the otu_labels in descending order.

### 2. Deliverable 2
------
Using my knowledge of JavaScript, Plotly, and D3.js, I created a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:

My code includes the following:

- The code for the trace object in the buildCharts(); function does the following:
-- Sets the otu_ids as the x-axis values
-- Sets the sample_values as the y-axis values
-- Sets the otu_labels as the hover-text values
-- Sets the sample_values as the marker size
-- Sets the otu_ids as the marker colors

The code for the layout in the buildCharts(); function does the following:
- Creates a title
- Creates a label for the x-axis
- The text for a bubble is shown when hovered over

### 3. Deliverable 3
------
Using my knowledge of JavaScript, Plotly, and D3.js, I created a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

- The code to build the gauge chart does the following:
- Creates a title for the chart.
- Creates the ranges for the gauge in increments of two, with a different color for each increment.
- Adds the washing frequency value on the gauge chart.
- The indicator shows the level for the washing frequency on the gauge.
- The gauge is added to the dashboard.
- The gauge fits in the margin of the <div> element.