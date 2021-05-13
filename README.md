# Information Visualization Course - Netflix Anaylsis

Information Visualization Course Project of MSc students from Unibuc-FMI:

- Cirstoiu Andreea-Ioana - Group 511 (Data Science)
- Iordache Florin-Nicolae - Group 507 (Artificial Intelligence)
- Ivan Andrei-David - Group 507 (Artificial Intelligence)

## Project overview

This project is named “Netflix Analysis” and its purpose is finding stories behind data from the dataset “Netflix Movies and TV Shows”. It can be found at the following link: https://www.kaggle.com/shivamb/netflix-shows,

The data was built using Flixable - a third-party Netflix search engine. They also provide a report analysing the number of movies and TV shows, providing information about all the productions added to Netflix until the beginning of 2021. Some of the included fields are:

- Title
- Type of production (Movie or TV Show)
- Added & release date
- Producing country
- Director & cast
- Duration
- Genre
- Description

## Technical perspective

The project is done in **Python**, using **Jupyter Notebooks**. Most of the plots are done using the **Plotly** library, while some are using **Matplotlib**. For data processing we are using **Pandas**, **numpy** and **networkx**.

## Data insights and types of charts

We have tried to find interesting conclusions based on fields like **production type**, **release date** and on the **relationships** between data fields, like producing countries and genre, or producing countries and release date.
Some of the question ideas which we came up with while processing the data and plotting it were:

- Which countries have produced the most titles?
- In what year have the most productions been added?
- Are there more TV shows than movies? How has this ratio changed over the years?
- What are the most popular genres on the platform?
- How are the actors collaborating between them?
- Is the average movie duration decreasing over the years?
- Which countries have the best rated movies?
- What words are the most widely used in descriptions?

The insights have been represented using several plot types, like **bar** charts, **line** charts, **stacked bar** charts, **treemaps**, **choropleth map** chart, **network** chart, **word clouds** and **sunburst** chart.

Most of the charts are interactive, such that the user can hover over data and see more precise information about it , or use sliders to change values represented on the chart (like current year) interactively.
