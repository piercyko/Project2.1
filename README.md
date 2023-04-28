# Project2.1

# Team Members

-  Chris Richards (https://github.com/Chris-Richards3/TableauProject)
- Claire Shur (https://github.com/claireshur/UFOSightings)
-  Kole Piercy (https://github.com/piercyko/Project2.1)
-  Jade Naughton (https://github.com/jnaug0829/Group-Project-2)
-  Jack Mannion (https://github.com/JackMannion01/TableauUFO)

# UFO Dataset
We used a data set that we obtained from kaggle.com that records UFO sightings. The rows of this data set are DateTime, city, state, country, shape, duration, comments, latitude, and longitude. The DateTime row describes clearly what day, month, year, and even what time of day that these sightings occurred. The city, state, country all specify where these recordings were located. The shape row is describing what these UFO’s looked like, whether it be a cylinder, circle, disk, or whatever that is recorded. The duration row is broken down by how long these sightings occurred. Some durations were a few seconds and some were a couple hours, there is quite a big range. Then the comments row are strings of text that the person who recorded the specific entry describes what they saw in the sighting. Some of them are super specific of what went down and what they saw, some are brief and a bit unclear, and some are just quite humorous, but they all describe the encounter. The latitude and longitude rows are super specific doubles that show exactly where these people were when they saw said UFO. 

# First Data Visualization
## Question 1: Does the distribution of UFO sightings correlate with the locations of airports in Georgia?

![alt text](https://github.com/Chris-Richards3/TableauProject/blob/main/distributionMap.png)

## Importance of this Question
The distribution of UFO sightings in Georgia gives insight to many elements of the reported data pertaining to the recorded cases. The first is geographical pattern; the cases can indicate a certain frequency within a particular city where an individual can have a high probability of seeing a UFO. The distribution also gives insight into the possible cultural and societal beliefs of the individuals in communities with high frequencies of reported sightings. A person in one city with no sightings may say there is no possibility of extraterrestrial life, while another person in a high-frequency city may advocate for extraterrestrial research. Delving further into cultural and societal beliefs, this may bring on an element of reporting bias within individuals of the same community; consequently prompting the question of credibility within the reported data. 

Expanding on the topic of credibility regarding reported UFO sightings, the question of correlation between the sightings of UFOs and locations of Airports may depict individuals perceiving flying objects incorrectly. Our group found that there is a correlation between high concentrations of UFO sightings and Airport locations within Georgia. This discovery calls into question the accuracy of reported sightings, ultimately questioning the validity of UFO sightings in general.


## Were there any manipulations or calculations that needed to be performed on the data, what were they? Describe the purpose and how they were accomplished.
We used a count of datetime in the UFO dataset to show the distribution of sightings because it was the best count of all reported sightings. Then, we filtered the sightings by ones reported in Georgia. Additionally, we added a dataset on U.S. airports, and then filtered them by region (Georgia) and by type, choosing only medium and large airports. We only included medium and large airports because by FAA categorization, a small airport receives 0.05 to 0.25 percent of annual U.S. commercial enplanements, which we deemed as relatively insignificant compared to the medium and large airports compared to UFO sightings. 

## Analysis & Results
According to the cartographic diagrams created, our group found that there is a strong correlation between high concentrations of UFO sightings and airport locations within Georgia. Each medium to large sized airport has a high number of UFO sightings surrounding these locations, with an exception to “SSI”. If an individual wanted to locate an area in Georgia that would have a high likelihood of a UFO sighting, our group would recommend the areas between Rome, Georgia and Atlanta, Georgia. 


# Second Data Visualization
## Question 2: How has the number of UFO sightings changed over time based on the 10 most popular shapes, in the United States? 

![alt text](https://github.com/Chris-Richards3/TableauProject/blob/main/lineChart.png)

## Importance of this Question
Looking into the different shapes of the UFOs will allow individuals to discern the uniqueness of a particular sighting. Also, identifying shapes of the UFOs are certainly important for possibly identifying these “unidentified” objects. Furthermore, differentiating UFOs by shape also helps one identify which shapes were more prevalent or “popular” at a certain time period. One could also try and correlate a popular UFO shape at a particular time and try to see if this is how UFOs were being presented in mainstream culture at this time.

## Were there any manipulations or calculations that needed to be performed on the data, what were they? Describe the purpose and how they were accomplished.
Our second data visualization utilized 3 filters that made our visualization easier to read and comprehend. The first filter was placed on the country the UFO sighting occurred in. We decided to focus only on sightings in the US which was reflected in our filter. The second filter we added was on the shape of the UFO sighting. Our data set included over 30 different possible shapes. We decided to add a filter on the 10 most common shapes to better visualize and identify any patterns in our visualization. The third and final filter we added was placed on the year the sighting was reported. The main reason to filter the data between the years 2000 - 2012 is due to a lack of data. The time frame we decided on has the most complete data which provides a more accurate representation in our data visualization.

## Analysis & Results
Through looking at the visualization, we were able to easily discern that the “light” shape is the most prevalent UFO sighting by a wide margin. Further, we found it interesting that as the number of UFO sightings grew, or shrank, the amount of sightings related to a certain shape also grew or shrank. Essentially, there was no shape that had an abnormally high or low amount of sightings in a period where there were a low or high amount of overall sightings. It was also interesting for us to note that none of these shapes “went out of style” as all of the sightings of certain shapes were on a consistent upwards trend instead of being on a downwards trajectory. 
