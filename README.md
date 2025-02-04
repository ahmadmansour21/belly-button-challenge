# belly-button-challenge
The code can be found in the app.js file in the static/js folder in the repository belly-button-challenge on Github.

All of the code was written independently and with the occasional help of Xpert AI tool.

First, the metadata panel was created using const metadata = data.metadata after accessing the data using d3.json --> filtering was done using .filter() --> panel.html() was used to clear any existing data --> finally, a loop was used to append with panel.append().

Next, function buildCharts was used to build the bar chart as well as the bubble chart:  const otuIds = result.otu_ids was used to get the otu_ids, otu_labels, and sample_values --> const bubbleTrace and const barTrace were used to create both charts as well as Plotly.newPlot() --> const barLayout to render the charts.

Finally, function init() to display them on the webpage -->  const dropdown = d3.select("#selDataset") to fix the dropdown menu.