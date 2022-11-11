# UFO - The Truth is Out There

### Overview of Project

The purpose of this project was to use JavaScript and HTML basics to build a website that enables visitors to review table data on UFO sighting reports, with a handy filter built in using JavaScript arrays to search by date, state, city, country and type (shape) of sighting. A section was also built in so that visitors can read a snippet from a UFOlogist about UFO sightings.


### Results

#### Page Header:

<img width="1464" alt="website_main" src="https://user-images.githubusercontent.com/105175961/201237530-7e5a200f-d3df-4d41-af71-42c77f8037d0.png">

The result of this project is a website with a clean, simple design and built-in search functions so visitors are able to review specific information related to our JavaScript arrays without having to browse the entire table. Visitors are able to search by specific dates, cities, states, countries and shapes of UFO sightings to learn more about them. The search fields are available on the left side of the page where users can input a single parameter and narrow down the table. 

#### Search function in action:

<img width="1469" alt="website_filtered" src="https://user-images.githubusercontent.com/105175961/201237559-eadf43df-8bdf-4f75-9ccb-3d52d9683ae3.png">


### Summary

In summary, we have a simple website design and styling that makes it easy and clear for visitors to our site to use a search function, allowing them to narrow down information on UFO sightings. 

##### Drawbacks

There are a few drawbacks I notice immediately when I begin to play around with the search filters. A calendar may be more helpful than letting users input a date as it is not clear what the date range is for the available information, and people may or may not type a date in the proper format. Also, the search fields are case-sensitive. If a visitor were to type "Spring Valley" instead of "spring valley" in the city search box, it would not return a result even though there is in fact a result for Spring Valley. This is especially troublesome considering people tend to automatically capitalize cities, states and countries.

##### Recommendations

I believe a couple of improvements to the code could make for better results. The main recommendation would be to remove case sensitivity on the search fields which as of now will limit results. Also, only one search parameter is permitted with the current code. If a site visitor wants to narrow their search by more than one valid element, their search will come up empty when otherwise it should not. 
