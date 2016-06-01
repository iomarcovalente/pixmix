# About pixmix
A simple webapp to fetch last uploaded images from the Flickr public API and display them neatly on a table-like fashion.

## Changelog:

##### Version 1.1.1 - Jun 1 2016
* Fixed items' layout breaking issue when closing Colorbox, which returned focus on Mini option bar anchor tag relative to the last picture shown, by adding "returnFocus:false"

##### Version 1.1.0 - May 31 2016
* Added functionalities: 
  + Colorbox lightbox integration for picture display on overlay <div>
  + Mini collapsible option bar on each item to show picture or remove picture from found pictures list 

##### Version 1.0.3 - May 30 2016
* Added functionalities:
  + smooth scrolling when a tag from a picture is selected
  + loading bar on search button to simulate a picture fetching process after a tag from a picture is selected

##### Version 1.0.2 - May 29 2016
* Fixed Images sliding bug for wider thumbnails on hover by replacing added padding with different positioning
* Added right padding between <li> for better display on when resizing window to two items per row
* Added viewport meta tag to improve layout functionality on smarthphones
* Added theme meta tag for smarthpones' browser tab styling

##### Version 1.0.1 - May 26 2016
* Added functionalities:
  + save results option
  + progressive pictures display 
  + search by pics' anchor tags

##### Version 1.0 - May 23 2016
* First release
