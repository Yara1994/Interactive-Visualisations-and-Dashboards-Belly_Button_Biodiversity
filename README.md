# Interactive-Visualisations-and-Dashboards-Belly_Button_Biodiversity

## My Heroku App - https://yarovoiapp.herokuapp.com/

In this assignment, we built an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

## Step 1 - Plotly.js

We used Plotly.js to build interactive charts for our dashboard.

## We had to:

## Create a PIE chart that uses data from your samples route (`/samples/<sample>`) to display the top 10 samples.

  * Use `sample_values` as the values for the PIE chart.

  * Use `otu_ids` as the labels for the pie chart.

  * Use `otu_labels` as the hovertext for the chart.



## Create a Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.

  * Use `otu_ids` for the x values.

  * Use `sample_values` for the y values.

  * Use `sample_values` for the marker size.

  * Use `otu_ids` for the marker colors.

  * Use `otu_labels` for the text values.



## Display the sample metadata from the route `/metadata/<sample>`

  * Display each key/value pair from the metadata JSON object somewhere on the page.

  * Update all of the plots any time that a new sample is selected.


## Step 2 - Heroku

Deployed our Flask app to Heroku. Link above!



