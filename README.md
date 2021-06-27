# Mission-to-Mars


## Overview

Scrape various websites for data related to the mission to Mars and build a flask app to display the information on a html page.


## Objectives

### Scraped Data:

#### NASA Mars News

#### JPL Mars Space Images - Featured Image

#### Mars Facts

#### Mars Hemispheres



### MongoDB and Flask Application:

* Use MongoDB with Flask templating to create a new HTML page to display all of the scraped data
* Convert Jupyter Notebook into a Python Script called `scrape_mars.py` with a function called `scrape` that will performe the scraping codes from above.
* Store the return value in Mongo db as a Python Dictionary
* Query the Mongo database and pass the Mars Data to an HTML template that can display the data
* Create a template HTML file to take the scraped Mars data and display in the appropriate HTML elements
