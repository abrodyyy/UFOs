# UFOs

## Project Overview

The goal of this project was organize a table of UFO data stored as a JavaScript aray and create a web page for users to view. Additionally, we've incorporated dynamic filters on the web page that allow users filter city, state, country, and shape simultaneously. 

## What You're Creating
This new assignment consists of one technical analysis deliverable and a written report. You will submit the following deliverables:
- Deliverable 1: Filter UFO sightings on multiple criteria
- Deliverable 2: A written report on the UFO analysis (README.md)

## Resources
- Data Source: [data.js](https://github.com/abrodyyy/UFOs/blob/main/static/js/data.js)
- Software: [Visual Studio Code, 1.70.2](https://code.visualstudio.com/updates/v1_70), [JavaScript](https://www.javascript.com), [HTML/CSS](https://html.com), [Bootstrap 4](https://getbootstrap.com)

## Results
Upon loading the UFO Finder web page [see link](https://abrodyyy.github.io/UFOs/) users are able to view all of the data on the site. 

![Home Page](https://user-images.githubusercontent.com/111623064/215447675-0b048ee6-a2ac-40f4-9c00-0b86339e653d.png)
![Home Page Data](https://user-images.githubusercontent.com/111623064/215447751-83b63fb5-8a61-441a-8159-c63472697e74.png)


They then have the option to filter by the categories shown below: 

![Filter](https://user-images.githubusercontent.com/111623064/215447805-4ebbedd1-e762-4bb9-b5fa-9b9109c3ad47.png)

Users can then filter by any or all categories they desire. 
- note: in order for the filter to take affect, they must click outside of the filter area. 

![example part 1](https://user-images.githubusercontent.com/111623064/215447863-cc457b43-ed0f-45d0-aa07-57f301b72bb0.png)

If they would like to filter more, they can go back and add more:
![example part 2](https://user-images.githubusercontent.com/111623064/215447906-a58a3a65-e158-4bac-832f-0b4f57601cd2.png)

In order to clear the filter critera, users must delete the text entered in the various filter categoreis: 
![Home Page Data](https://user-images.githubusercontent.com/111623064/215447946-21c394ea-fee4-462c-9924-615bf925e787.png)

## Summary
In order to allow users to filter for multiple critera rather than just date, we had to remove the "filter" button originally present on the page. This could lead to confusion, as users must click outisde of the filter area in order for the filter to take affect. I would reccomend that in the future, a new filter button that works with the multiple filters to avoid confusion. Additionally, in order to clear the fitlers, users must go back and delete all the text entered. I would reccomend in the future adding a "clear filters" button as well. Finally, I would reccomend adding more dynamic assistance to the filters, such as a calendar box for the date, drop downs with heirarchy encoded for the rest. For example: if a user were to enter 1/1/2010 as the date, when they moved to the next filter, a drop down would list the cities, state, countries, and shape with data available for that date.  
