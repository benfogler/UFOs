# UFOs

## Overview of the Project

### Purpose
The goal for this project was to build a webpage capable of filtering data about UFO sightings using JavaScript, HTML and CSS. The webpage will have a filter
so that you can view your data by specific points such as: date, city, state, country, and shape.

### Link to site
[https://github.com/benfogler/UFOs](https://github.com/benfogler/UFOs/blob/main/index.html)

### Results
As you can see in the below image, the site is build with a statement, Filter Search, and table filled with data. You can also see that we leveraged CSS to 
import a background of Earth from space. Having this filter will allow the individual to determine different possibilities like which state may have the most sightings.

![the_truth_is_out_there](https://user-images.githubusercontent.com/114610539/209689295-eb727f9e-5215-4a41-91ed-1ed53e8410d3.png)

### Summary
One issue I have with the table is the lack of consistency in the duration column (date/time formats different). If you were to try and sort by this column
it would be nearly impossible due to the different formats.

One thing I would consider doing is standardizing the datetime format so that it was consistent for each row, and then drop any unknowns. 

The second thing I would do is consider adding a sortby function to the filter/table so that one could sort in specific orders if they choose too.
