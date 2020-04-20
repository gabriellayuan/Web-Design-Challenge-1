# Web Visualization Dashboard (Latitude)

### Overview:

 A Dashboard website to visualize the weather of 500+ cities across the world of varying distance from the equator using HTML5, CSS3 and Bootstrap. Specifically, we will be plotting weather data.
 
 In this dashboard, each plot has an individual page and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. We also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.
 
 The live deployed website can be found here: [Web Visualization Dashboard](https://hrao-dev.github.io/WebVisualizations/index.html)
 
The website consist of 7 pages total, including:

* A landing page containing:
    * An explanation of the project.
    * Links to each visualizations page.
* Four visualization pages, each with:
    * A descriptive title and heading tag.
    * The plot/visualization itself for the selected comparison.
    * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
    * Contains all of the visualizations on the same page so we can easily visually compare them.
    * Uses a bootstrap grid for the visualizations.
* A "Data" page that:
    * Displays a responsive table containing the data used in the visualizations.
      
The website, at the top of every page, has a navigation menu that:

 * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
 * Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
 * Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
 * Is responsive (using media queries)
