# Web Visualization Dashboard

## Background

This project is focused on creating a visualization dashboard by plotting [weather data](Resources/cities.csv).<br>
Each page contains visualization and corresponding explanation.<br>
On a landing page you can see a comparison of all of the plots.<br>
Data page contains information used for building visualizations.

## Web Dashboard Features 

The dashboard consist of 7 pages total, including:

* A **landing page** containing:
  * An explanation of the analysis.
  * Links to each visualizations page.
* **Four visualization pages**, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A brief description of the plot.
* A **"Comparisons" page** that:
  * Contains all of the visualizations on the same page.
  * Uses a bootstrap grid for the visualizations.
* A **"Data" page** that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML. 

**Dashboard** contains navigation menu at the top of every page that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.

## Installation 

Clone this repository to your local machine and double click on `index.html` file to see the visualization.<br>
For styling properties please refer to [`css file`](html_css/style.css).