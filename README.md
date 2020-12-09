# Mission-to-Mars

## Overview
Help Robin to update her web app by using BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of the hemispheres, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Summary:

### 1.	Scrape Full-Resolution Mars Hemisphere Images and Titles
In the Mission_to_Mars_Challenge.ipynb three for loops were created:

a)	The first for loop is to retrieve the titles of the hemispheres and place them in a list “titles = []”. 

b)	The second for loop is to retrieve the links of each image of the hemispheres, here the list “titles = []” was used to loop through each hemisphere. With the for loop the following actions were completed: 

  •	click on each hemisphere link

  •	navigate to the full-resolution image page and retrieve the full-resolution image URL string for each hemisphere image. A list “img_urls=[]” was created in this for loop. 

c)	The last for loop is to fill up the empty dictionary “hemisphere_image_urls={}” with the lists “titles=[]” and “img_urls=[]”.


### 2.	Update the Web App with Mars’s Hemisphere Images and Titles

Using Python and HTML the web app was updated with now the images and names of Mars hemispheres.

### 3.	Add Bootstrap 3 Components

The web was updated by making it mobile responsive and several Bootstrap 3 were added to make it stand out.

When using the DevTools the responsiveness of the website can be tested by changing the type of device in the Toggle Device Toolbar.

Bootstrap 3 that were added:

1.	In the header area:

  •	The jumbotron has a background image as the style.
  
  • The title “Mission to Mars” is in a lighter color to stand out from the new background.
  
  •	The button that was previously blue now is orange, just to match with the background.

2.	The “Mars Facts” table was upgraded to a “hover” table (this change was made in the “scraping.py” document).

3.	The page header “Mars Hemisphere” was upgraded with a jumbotron with an image as its background and with a change in the text color.
