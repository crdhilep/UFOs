# UFOs

## Overview

The purpose of this project was to create a webpage with a dynamic table that shows information regarding UFOs based on multiple interactive filters that can be applied to narrow down the information search based on the user's desired input and criteria. The webpage was also lightly customized to make the page look more appealing and easy on the eyes. This was done using HTML, CSS, Bootstrap and Javascript.

## Results

In order to allow users to perform a search for the specific criteria, list elements were added into the index.html file for each filterable criteria (date, city, state, country, and shape). To keep track of all elements that change when a search is performed, a filters variable was created in the app.js file that stores the property "id" and the value entered from the user's input. For aesthetics, a placeholder was also included to give the user a sort of template value to enter.

Before a search is done, the table to the right shows all existing data, as this table has not yet been filtered to any criteria yet.

![Before Applying Filter](/resources/Before_Applying_Filter.png)

Once some criteria have been entered however, the table of data to the right changes accordingly to deliver the results that the user requested through the search. Below Image show a search criteria for the specific city:

![After Applying Filter](/resources/After_Applying_Filter.png)
