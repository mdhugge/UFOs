# UFOs
## Overview of Project
Using JavaScript to create a dynamic webpage on UFO sightings. The webpage displays data on various UFO sightings in a table format. Users are able to filter the data in the table to refine their search based on date, city, state, country and shape. 

## Results
To the left of the table on UFO sightings is a section that allows users to apply filters and refine their search, as shown below.

![Filters](https://github.com/mdhugge/UFOs/blob/main/static/images/Filters.png)

Users can refine their search based on Date, City, State, Country and Shape.

### Using Search Criteria
The user can enter a value into each of the input boxes and than press ENTER in order to apply the filter to the table.

To remove a filter the user has to clear the input box and press ENTER

#### Filtering for Date
The date should be entered in the format of Month/Day/Year (e.g. January 13, 2010 would be entered as 1/13/2010).

Applying a date filter of 1/13/2010 would return the following result:

![Date_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/Date_Filter.png)

#### Filtering for City
The city should be entered in all lower case letters (e.g. El Cajon would be entered as el cajon).

Applying a city filter of el cajon would return the following result:

![City_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/City_Filter.png)

#### Filtering for State
The state should be entered in with the two letter state abbreviation (e.g. Pennsylvania would be entered as pa).

Applying a state filter of pa would return the following result:

![State_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/State_Filter.png)

#### Filtering for Country
The country should be entered in with the two letter country abbreviation (e.g. Canada would be entered as ca).

Applying a country filter of ca would return the following result:

![Country_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/Country_Filter.png)

#### Filtering for Shape
The shape should be entered in all lower case (e.g. Circle would be entered as circle).

Applying a shape filter of circle would return the following result:

![Shape_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/Shape_Filter.png)

### Filter Value Does Not Exists
If the filter value entered by the user does not exist an empty table will be returned. 

Applying a shape filter of diamond would return the following result:

![Diamond_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/Diamond_Filter.png)

### Multiple Filters
Users can also enter values for multiple categories.

Applying the following filters: Date = 1/13/20, City = el cajon, State = ca, Country = us, Shape = triangle would return the following result:

![All_Filter](https://github.com/mdhugge/UFOs/blob/main/static/images/All_Filter.png)

## Summary

A drawback to the current design is that the users input has to match the information in the data completely. If the value does not match completely no results will be retrieved. Something as simple as adding a space to end of the input value can lead to no results.

To improve the webpage the filter values could be presented as drop-down list, where the user can choose a filter from the list. This would also lower the chance of returning no results due to a spelling error or an additional character.

Another change that can improve the user experience is to apply the filters by looking for partial matches to the value entered by the user instead of exact text. This would require modifying the code so that matches to the beginning, middle or end of the text value is searched. 

