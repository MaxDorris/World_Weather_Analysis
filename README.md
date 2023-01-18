# World_Weather_Analysis

## Summary
I utilized OpenWeatherMap (OWM) API to gather weather data for "closest cities" using randomly generated coordinates. A dataframe to store cities and their corresponding current-weather report (free with OWM) was created with the Pandas library. Using the cities' documented coordinates, a nearest hotel was found (if possible) using Geoapify. The hotels were then added to a new dataframe. Using Holoviews and user inputs for high and low temperature values, a map was created from this new dataframe to show cities with hotels with maximum temperatures within this range. Several cities were seleted within drivable distance of eachother, and a routing overlay (as you would find through adding stops to Google Maps) was created using Geoviews.

Applications of this process could be useful in a vacation itinerary planning service. However, there are plenty of other applications for it, such as: food-delivery, prescription-delivery, locating and routing to a nearest hospital, mapping food deserts, and measuring general "drivability" of a given search area.
