# UFOs

## Overview 

In this project an application was created to display UFO sightings on a webpage based on location, date, and shape.

The primary tool used for this application was JavaScript.  Javascript is increasingly used in advanced programming and machine learning settings. It is also used to make websites more functional and dynamic.  In addition to Javascript, HTML and CSS were used to complete the webpage.





## Results:

Four files were created to present the webpage.  These are the [html.index](https://github.com/rciminera/UFOs/blob/main/html.index), [app.js](https://github.com/rciminera/UFOs/blob/main/html.index), [data.js](https://github.com/rciminera/UFOs/blob/main/html.index), and [style.css](https://github.com/rciminera/UFOs/blob/main/style.css) files.



### Project Deliverables

I. Filter Elements:

Five list elements for filtering were created in the index.html file. These list elements are date, city, state, country, and shape.

II. Event Listener:

The event listener set up to detect changes to each filter in the app.js file. When data is entered into any one of the 5 filters, the following code senses that a change was made from the default values when the web page is initially loaded.

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/listener.png)

III. Create a Filter Function

The listener will call the updateFilters() function whenever htere is a change in any of the filters.  This function saves the element, value, and the id of the filter that was changed.  

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/updateFilters.png)

IV. Create Table of Filtered Data

The filterTable() function is called by the updateFilters function.  This function loops through all of the filters and keeps any data in the original data.js file that matches the filter values.

V. Create Webpage

The UFO webpage filters webpage filters the table correctly based on user input. 

![GitHubLogo](https://github.com/rciminera/UFOs/blob/main/Screenshots/UFOs_webpage.png)


Summary:

The summary addresses one drawback of this webpage

- 
- city state combinations invalid  eg Roswell, Ca is not a valid city state pair
- introductory text could be updated real time and could easily get stale
- country 

The summary addresses two additional recommendations for further development

- Clean up of the raw data &#44
- Standardize on the duration format to be a datetime function with duration in hrs, minutes
- Fix the default 
- City, state, country validation upon entry






