# UFOs

## Overview 

In this project an application was created to display UFO sightings on a webpage based on location, date, and shape.

The primary tool used for this application was JavaScript.  Javascript is increasingly used in advanced programming and machine learning settings. It is also used to make websites more functional and dynamic.  In addition to Javascript, HTML and CSS were used to complete the webpage.

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/opening_webpage.png)



## Results:

Four files were created to present the webpage.  These are the [html.index](https://github.com/rciminera/UFOs/blob/main/html.index), [app.js](https://github.com/rciminera/UFOs/blob/main/html.index), [data.js](https://github.com/rciminera/UFOs/blob/main/html.index), and [style.css](https://github.com/rciminera/UFOs/blob/main/style.css) files.



### Project Deliverables

I. Filter Elements:

Five list elements for filtering were created in the index.html file. These list elements are date, city, state, country, and shape.

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/five_elements.png)

II. Event Listener:

The event listener set up to detect changes to each filter in the app.js file. When data is entered into any one of the 5 filters, the following code senses that a change was made from the default values when the web page is initially loaded.

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/listener.png)

III. Create a Filter Function

The listener will call the updateFilters() function whenever htere is a change in any of the filters.  This function saves the element, value, and the id of the filter that was changed.  

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/updateFilters.png)

IV. Create Table of Filtered Data

The filterTable function is called by the updateFilters function.  This function loops through all of the filters and keeps any data in the original data.js file that matches the filter values.

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/filterTable.png)


V. Create Webpage

The UFO webpage filters webpage filters the table correctly based on user input. 

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/webpage_table.png)


Summary:

By entering specific values for any or all of 5 values the webpage will display data for the values chosen.  In the event that nothing is entered all data for Jan 10, 2010 is displayed. 

The webpage functions as designed but there are at least 2 drawbacks: the data has not been scrubbed to elimate textual errors and the duration entries could be set in a standard date time format for consistency.

Recommendations for futher development on the webpage include:

- Clean up of the raw data using regex functionality to eliminate input errors such as &#33 which cnvey no meaning to the description
- Standardize on the duration format to be a datetime function with duration in hrs, minutes, secs
- Modify the graphic background to keep the website fresh 
- Enhance the opening paragraph to display current events in the controversy surrounding UFO's.








