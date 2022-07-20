# UFOs :alien: 

## 1. Overview 

The purpose of this challenge is to get a dynamic table that provides an in-depth analysis of UFO sightings by allowing users to filter for multiple criteria. Table filters include date, city, state, country, and shape.

## 2. Instructions 

### 2.1. Filter using a single text input field

![](https://github.com/AllenAx91/UFOs/blob/main/static/images/Screen%20Shot%202022-07-20%20at%206.34.21%20PM.png)

Let's consider the first field, "DATE". A place holder has been introduced into the HTML to provide users with the date format that needs to be entered. This would avoid input errors and result in the desired filtered table. In addition, the file only recognizes dates that are already in the table. 

Once the desired date has been entered into the field, shift the pointer to the next field or press Enter to enable the updateFilters() function. You will now witness the table change instantaneously to display only rows that match the date entered. 

### 2.2. Filter using multiple text input fields

![](https://github.com/AllenAx91/UFOs/blob/main/static/images/Screen%20Shot%202022-07-20%20at%206.27.10%20PM.png)

Let's enter El Cajon as City which would bring up five rows. To narrow it down to a single date, enter the desired date among the filtered table. Now the filter gets updated and a new table appears considering both the inputs. Similar to the previous step, move the pointer to the next field or press enter to update the filter. This process can be repeated for all fields and the table would get filtered based on the matching data. 

## 3. Summary

### 3.1. The drawback to the design

The div.col-md-3 element that holds the filter search box can be moved to the space above. The table will have more space and more rows can be displayed on one page

### 3.2. Recommendations for further improvement 

1) The website would eventually need live data by scrapping through reliable sources and storing them in MangoDb. 

2) Links to the source can be another improvement 
