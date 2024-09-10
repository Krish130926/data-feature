# data-feature weather-Based Event Finder

This Jupyter Notebook demonstrates the creation of a simple data feature prototype that helps users find events based on current weather conditions using the Weatherstack API and the GitHub Events API.

Features:
•	Retrieves current weather for a specified city using the Weatherstack API.
•	Searches for public GitHub events using the GitHub Events API, based on the weather conditions (e.g., outdoor events for sunny weather, indoor events for cloudy/rainy weather).
•	Displays up to 10 recent GitHub events related to the weather conditions in the selected city.

How to Use the Feature:
1. Input a Location:
The user enters the name of a city (e.g., "New York").
2. Weather Data Retrieval:
The system queries the Weatherstack API for the current weather conditions in the specified city.
3. Event Selection Based on Weather:
Based on the weather description (e.g., "Sunny," "Cloudy"), the system decides to fetch either "outdoor events" or "indoor events" from the GitHub Events API.
4. Event Display:
The system displays a list of public GitHub events matching the weather-based criteria.


Prerequisites:
To run this notebook, you will need to set up API keys for:
•	Weatherstack API (for retrieving weather information by location): Sign up for an API key at Weatherstack.
•	GitHub Events API (for searching events). 

Notes:
API Keys: To utilize this notebook, you must have valid API keys for both the Weatherstack API and the GitHub Events API. 
Weather Descriptions: The system categorizes weather conditions into broad types (e.g., "Sunny," "Cloudy"). The mapping of these descriptions to event types (e.g., outdoor or indoor) is simplistic and can be customized for more accurate results.
Usage:
Set Up API Keys:

Obtain your API key from Weatherstack by signing up at Weatherstack.
Obtain a GitHub Events API key from GitHub API if required (GitHub APIs are often public, but a key might be needed for extensive queries).
Prepare the Notebook:

Replace the placeholder API keys in the notebook with your actual API keys.
Input a Location:

Locate the input cell where you will enter the name of a city. Example: New York.
Retrieve Weather Data:

Run the cell that queries the Weatherstack API to get the current weather conditions for the specified city.
Select and Display Events:

Based on the retrieved weather description, the notebook will fetch and display a list of public GitHub events that match the weather-based criteria (e.g., outdoor events for sunny weather).
Review and Analyze Events:

Examine the displayed events to see if they align with the weather conditions and your interests. Adjust the event criteria or weather categorization as needed for better results.
