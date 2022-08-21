# World_Weather_Analysis
Module 6


At the most fundamental level, Jack needs help answering a question: How might we provide real-time suggestions for our client's ideal hotels? Your first task was to define what you meant by "ideal." So, over the course of the conversation, you narrowed that to hotels that were (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for the client.

Here's an outline of your project plan:

Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

Created three seperate files, first one stores the weather for multiple ciites after gernerating random pairs of lat and long cooridnates and generating ciites.  Once that list is generated, it pulls the weather data from google so we can create an entire database of information for each city.

The second file created builds hotel information for the list of cities and creates a map showing the spots for eah city where a user can select the city map point and it displays the hotel in the city and the weather for that city.

The third file then helps generate a road trip map for 4 cities a user would like to travel to within a country. Once the 4 cities are selected, it then displays the driving map between all four cites from start to finish of the trip and also them creates a map with the four points on it so the user can pull up the weather info for that city as well.