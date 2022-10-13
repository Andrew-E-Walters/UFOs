# UFOs

# Overview of the project
## Background
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we will add table filters for the city, state, country, and shape.

![](https://github.com/Andrew-E-Walters/UFOs/blob/main/images/Completed%20Module.png)

As we can see the data right now will only filter to the date. While that is helpful for analysis, it would be more beneficial for the filter to be able to handle multiple criteria. Looking at the data.js file we can see that there is more that could be filtered. 

![Data](https://github.com/Andrew-E-Walters/UFOs/blob/main/images/Exaple%20of%20Data.png)

We can see that Datetime, City, State, Country, Shape, Duration, and comments are able to be looked at with each set of data. Including a few of these to our filter would allow us to do more analysis. The data could have significance in researching how the UFO sightings differ by state or country. We might be able to track and see if it was traveling across certain locations on the same night if our filter is set to catch it. We will have to start by adding the filters. 

# Results

#### Webpage with multiple filters
![](https://github.com/Andrew-E-Walters/UFOs/blob/main/images/Completed%20Module%20Challenge.png)

## Performing a search 
Through updating our code to take in multiple conditions in all the possible data points that can be filtered, we are able to gather data in a more effective manner. Where before we were limited by only one filter option, we can now create search criteria in our filter that can return highly specific data. When I added all the filters, I could then search using my desired filters and return all the way down to a single data point. Below is an example of just how specific this code can get. 

![Images of Search step by step](https://github.com/Andrew-E-Walters/UFOs/blob/main/images/One%20Search%20Example.png)

In the Module we only had the date filter. Now that we have added the other filters, we can then enter other information criteria to their respective filters. For example, we can enter the Datetime, City, State, Country, Shape. I wanted to see what UFOs if any happened in Round Rock TX, USA and only there. The results above are what I was able to see. It returned the one instance that fit all the criteria in my filter. 

# Summary
## Drawback 
One thing that I have identified as a drawback is that our search bar does not have a feature where we could group the sightings by the comments on the description of the UFO. 

![Benton Data](https://github.com/Andrew-E-Walters/UFOs/blob/main/images/Benton.png)

For example: the comment on one of the UFO’s being “4 Bright Green Circles” would possibly be more credible or valuable if we could filter based on that description to see if that was a common sighting or if this was the only case. If we then identify a similar description of a UFO that could give more credibility to the story and could help us in our research. Right now we are unable to see if there is a pattern in the comment data.

## Recommendation
1.	I would include a filter based on key words in the comments section of the data that grabs UFO sightings based on similar descriptions. This would help in our research greatly and could prove to be more vital than other filter criteria. 
2.	I think that visualizing the data would be beneficial. If we were able to create a visual heatmap of UFO sightings that would display on the website, then that could allow us to get a better sense of where people are seeing UFOs. 
