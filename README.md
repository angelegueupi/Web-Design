# Web-Design-Challenge
![image](https://user-images.githubusercontent.com/106934375/186811732-24083c3a-5f32-4285-8de5-e75ffdac0fe0.png)

Instructions
Create a website by using either the visualizations that you created for your Python-APIs Challenge or the weather data and images that are provided for this Challenge. To do so, use the considerations and website requirements that the following subsections describe. Also, ensure that your repository has regular commits and a descriptive README.md file.

# Website Requirements
The overall requirements for your website are as follows:

Your website must consist of seven pages.

At the top of every page, your website must have a navigation bar.

Your website must be deployed to GitHub Pages.

Next, we’ll describe these requirements in detail.

Your website must consist of seven pages as follows:

A landing page that contains the following elements:

An explanation of the project.

A link to each visualization page. For these, a sidebar should contain a preview image of each visualization. Clicking an image should take the user to that visualization.

Four visualization pages, stored in the visualizations folder, each with the following elements:

A descriptive title and a heading tag.

The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the assets/images folder.

![image](https://user-images.githubusercontent.com/106934375/186811943-7770e082-538a-4d3e-abbd-d91aef0f5106.png)



A paragraph describing the visualization and its significance.

A comparisons page that does the following:

Contains all the visualizations on the same page so that people can easily compare them.

Uses a Bootstrap grid for the visualizations. This grid must contain two visualizations across a medium or large screen and one visualization across an extra-small or small screen.

A data page that displays a responsive table containing the data that the visualizations use, as follows:

The table must be a Bootstrap table component.
The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a to_html method that generates an HTML table from a Pandas DataFrame. To learn more, see pandas.DataFrame.to_html (Links to an external site.) in the official Pandas documentation.
![image](https://user-images.githubusercontent.com/106934375/186812519-dcbea6ef-f266-4230-9e7c-e27321cf5f7f.png)


At the top of every page, your website must have a navigation bar that does the following:

Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.

Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualization page.

Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.

Is responsive (via media queries). Note that the navigation bar must resemble the one in the screenshots in the Navigation Bar section. In particular, notice the background color change.

Your website must be deployed to GitHub Pages:

As a result, the website must work at a live, publicly accessible URL. Save this URL for your later submission.

