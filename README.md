# Mission-to-Mars

# Project Overview

The purpose of this project is to create an website that shows information about Mars. The displayed info was scraped from NASA website and couble be the latest news and images. In order to deploy this, we need to prepare 3 files, which are scraping file to scrape data from NASA website, a Flask web applicaton and a rendered HTML file to show all the scraping data. 

# Resources

- Scraped Website:

  https://data-class-mars.s3.amazonaws.com/Mars/index.html
  
  https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html
  
  https://galaxyfacts-mars.com
  
  https://marshemispheres.com/
  
- Softwares: Python, Jupyter Notebook, MongoDB, HTML

# Results

We created scraping code in Jupyter Notebook first by using Splinter, Beautiful Soup, Webdriver-manager, and Pandas. The code scraped the latest new, images, fact of Mars. Then we export it as python file. 

Next we build a Flask web applicaton and HTML file to show all the scraping data. The website is the following:

![Mission-to-Mars](https://github.com/ivorfanning/Mission-to-Mars/blob/main/mission_to_mars_webpage.png)

# Summary

As we can see from the above website, every time I want to check the latest news and images, the only thing to do is to click the 'Scrape New Data' button, the application will automaticlly scarpe the new data for viewers. Another cool feature is the webpage is mobile-responsive, meaning you could view it on any mobile devices.
