# Web Design - Web Visualization Dashboard (Latitude)

## Background



![Images/landingResize.png](Images/landingResize.png)


## Latitude - Latitude Analysis Dashboard
[weather data](Resources/cities.csv).


### Website details 

For reference, see the ["Screenshots" section](#screenshots) below.

* A [landing page](#landing-page) containing:
  * Here i created a dashboard with individual pages for each plot and tabs to navigate between them. Each page contains visualizations nad corresponding explanations. The landing page is where we can see the comparison of all the plots and a page of the data aquired to build them,
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)



### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:<img width="472" alt="08-Media-Inspect-After" src="https://user-images.githubusercontent.com/33403205/150706003-d5b75c86-cc0d-415b-8098-3c8a0894f63f.png">


![Landing page large scre<img width="1185" alt="07-Media-Inspect-Before" src="https://user-images.githubusercontent.com/33403205/150706015-9b4dee37-b64b-4478-98fe-331b7f35b39d.png">
en](Images/landingResize.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](Images/data-lg.png)

![Screen Shot 2022-01-23 at 7 02 51 PM](https://user-images.githubusercontent.com/33403205/150706052-14363f84-eccf-4fac-be4d-b6aec28536e5.png)

Small screen:
![citywindspeed](https://user-images.githubusercontent.com/33403205/150706086-62db3196-e745-450b-9cb1-b25041f9f4e5.png)

![data page small screen](Images/data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:
<img width="1048" alt="06-Devtools" src="https://user-images.githubusercontent.com/33403205/150706060-47aba9ae-192b-4af0-8a0c-82b89389ea11.png">

![visualize page large screen](Images/visualize-lg.png)

Small screen:
![citycloudiness-3](https://user-images.githubusercontent.com/33403205/150706064-6147ebad-c0c2-44d2-806c-72f5b21bd41d.png)

![visualize page small screen](Images/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu
![citylatitude](https://user-images.githubusercontent.com/33403205/150706069-4d69c9f3-31c1-4826-b1c7-92d42d46c94f.png)

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:![cityhumidity](https://user-images.githubusercontent.com/33403205/150706075-0bb607e8-ce17-4e8d-8133-8492bcb5cd7f.png)

![nav menu small screen](Images/nav-sm.png)

- - -![citytemperature](https://user-images.githubusercontent.com/33403205/150706079-b558b3ef-a156-4bea-9a87-e196a32c02a1.png)


## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
