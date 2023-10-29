# belly-button-challenge

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


Following steps have been completed:

1. Use the D3 library to read in samples.json from the URL https://     2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

a. Use sample_values as the values for the bar chart.

b. Use otu_ids as the labels for the bar chart.

c. Use otu_labels as the hovertext for the chart.

bar Chart

3. Create a bubble chart that displays each sample.
a. Use otu_ids for the x values.

b. Use sample_values for the y values.

c. Use sample_values for the marker size.

d. Use otu_ids for the marker colors.

e. Use otu_labels for the text values.

Bubble Chart

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

hw

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
hw


References
Challenge 14 classpresentation and materials
https://plotly.com/javascript/gauge-charts/
https://code.tutsplus.com/create-interactive-charts-using-plotlyjs-pie-and-gauge-charts--cms-29216t