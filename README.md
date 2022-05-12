# UFOs

## Overview

This project aims to build a functioning website hosted through GitHub Pages that displays UFO sighting data based on user filters. The data covers worldwide sightings over a three day period between January 10, 2010 and January 13, 2010. The dataset was provided by our client, Dana. The site allows a user to search through our dataset for various criteria, to provide a platform for further study. The site uses D3 for event handling, and comprises of HTML, JavaScript, and CSS components. 

## Results

The site is public and may be reached [at this link.](https://ipbrieske.github.io/UFOs/). A user is initially presented with a discussion of the hazards inherent to investigating extraterrestrial life, and encourages the user to proceed at their own discretion. The table of data follows a number of search crtieria that the user may filter for: Date, City, State, Country, and Shape (of the observed anomaly). 

![Filter Search](https://github.com/ipbrieske/UFOs/blob/main/Images/search.png)

Entering data into a search field and pressing "Enter" will reload the table with only the data matching the search criteria. 

![Filtered Data](https://github.com/ipbrieske/UFOs/blob/main/Images/filter.png)

Furthermore, additional search filters may be applied, to search for more specific observations. 

![Multi-Filter](https://github.com/ipbrieske/UFOs/blob/main/Images/multifilter.png)

## Summary

While we are currently quite satisfied with the state of the site, many improvements can be implemented to improve the user experience. The chief current drawback is the case-sensitivity of the search filters. This could be ameliorated by converting search criteria to capitalized letters when searching for matches. 

Additionally, the site can be further developed by expanding the dataset available. My recommendation would be to find more external sites that contain UFO sighting information. Through the use of APIs or webscraping, the dataset can be updated each time a user searches for information. To speed data retrieval, the dataset could be stored on a MongoDB database using PyMongo instead of a .js file. This way, the dataset can grow over time and provide updated results to users. Once the scraping/data retrieval is automated, the site can run until maintenance becomes necessary. 
