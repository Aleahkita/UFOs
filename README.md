# UFOs


## Overview 

The purpose of this project was to create a dynamic webpage that allows the user to filter UFO sightings on multiple criteria. Table filters were added for the city, state, country, and shape in addition to the date filter from the first webpage created. This will allow users to refine their search of the UFO sighting dataset to find specific sightings of interest. In addition to more filters, the button was replaced with an event listener that will automatically update the table as filter criteria is updated or changed.


## Results 

The webpage is initially populated with the full dataset within a table and a section for applying filters. 

(insert image 1 of full webpage)

Within each filter's input box is an example of possible user entries. Following the format of the example within each input box, the user can enter in their own search criteria for the date, city, state, country, and shape details of sightings. 

(insert image 2 of filter box)

When the filter(s) are changed, the table will automatically update with results matching the criteria. 

(insert image 3 of updated webpage after filters.


## Summary

One drawback of the new design is that without a designated 'Filter' button, when the user is finished inputing a single or multiple filters, the update in the table has to be triggered by an additional click elsewhere within a filter field. Despite the event listener waiting on an update in the filters, the webpage does not update the table without clicking away from the final input field. 
One recommendation for further development is to add the 'Filter' button back. Without one, there could be some confusion on the user's end when they try to apply the first or final filter in their search. Another recommendation is to add a dropdown menu for the shape filter. The dropdown menu would contain all of the possible shapes of the sightings since there could be shapes that the user might not consider. Showing the user all of the available options could help them refine their search.
