# plotly_deployment

# **Summary**
----------------------

- Using the given research data, we were asked to create a dymanic dashboard to help represent the data.  Given the collected data was local and would need to be accessed we had to come up with a way to get around the Cross-Origin Resource Sharing (CORS) issues.  We can get passed this roadblock by creating a local server on our own PC, but to allow the world to view this data we will have to use the GIT Pages, which acts as a local server.  Below is the link that allows you to see our visualization for the given data. 

1.  We created a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage.
2.  We create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:
    - The otu_ids as the x-axis values.
    - The sample_values as the y-axis values.
    - The sample_values as the marker size.
    - The otu_ids as the marker colors.
    - The otu_labels as the hover-text values.
3.  We created a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

Please visit the link below to view the data and the viusalization

https://bionicbabes.github.io/plotly_deployment/
