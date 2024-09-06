# Nearest Hotel availability & Recommendation system 
Filters Available For Hotels Recommendation as per location, Required City Range, weather requirements, Temp inputs and avaibility for Future Holiday and Vacation destination Trips In Required City
<img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/fbc52262225969.5a89af053bacd.gif" alt="Project 14">
### This activity was broken down into two deliverables, WeatherPy and VacationPy.

# Part 1: WeatherPy
In this deliverable, created a Python script to visualize the weather of over 500 cities at varying distances from the equator. used the Citipy Python library, the OpenWeatherMap API, and your problem-solving skills to develop a representative model of weather across cities.
![image](https://github.com/user-attachments/assets/2c9c47ce-f807-441a-8f57-50835276a2ea)

- For this part, used the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code guided through the process of using your Python coding skills to develop a solution that addressed the required functionalities.
- To get started, the code required to generate random geographic coordinates and find the nearest city to each latitude and longitude combination was provided.
![image](https://github.com/user-attachments/assets/5ddc107a-9239-495d-b2f2-a555b54ff1bd)
![image](https://github.com/user-attachments/assets/d622a224-0c75-4728-9d91-918f7775a012)

# 1. Visualizing Weather Variables: 
Using the OpenWeatherMap API, you retrieved weather data and created scatter plots to examine the relationships between latitude and various weather variables, including temperature, humidity, cloudiness, and wind speed.

# 2. Computing Linear Regression: 
For each weather variable against latitude, you computed linear regression to analyze trends. The analysis was divided into Northern Hemisphere (≥0° latitude) and Southern Hemisphere (<0° latitude) to identify any distinct patterns. Scatter plots were created with regression lines, model formulas, and R² values to illustrate these relationships.

## Requirement 1: Created Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, 
### used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Then, created a series of scatter plots to showcase the following relationships:
![image](https://github.com/user-attachments/assets/80058ed7-2c15-46de-b1d2-4e443f9eb6e1)
![image](https://github.com/user-attachments/assets/667d2eef-b9a9-4691-aba6-d03b5debb42d)
![image](https://github.com/user-attachments/assets/ab068d7b-13b8-492e-9edf-a57959cfd195)
![image](https://github.com/user-attachments/assets/98b4e244-2382-460d-a79a-729f790945df)
![image](https://github.com/user-attachments/assets/a8b9a469-03e5-40c0-95e8-96f5ddd79df6)

- Latitude vs. Temperature  
  ![image](https://github.com/user-attachments/assets/0b52dc56-fdc1-4c0b-acbd-af53cf15958e)
  
- Latitude vs. Humidity  
  ![image](https://github.com/user-attachments/assets/4029cbfc-2923-4d25-84a1-ffd814da964d)
  
- Latitude vs. Cloudiness
  ![image](https://github.com/user-attachments/assets/8775ac81-7f9d-4686-aeed-362f271784d9)
  
- Latitude vs. Wind Speed  
 ![image](https://github.com/user-attachments/assets/92ad6dac-4fc2-4d19-9a64-b73b4f5650c3)

## Requirement 2: Computed Linear Regression for Each Relationship
To fulfill the second requirement, 
### computed the linear regression for each relationship. The plots were separated into the Northern Hemisphere (greater than or equal to 0 degrees latitude) and the Southern Hemisphere (less than 0 degrees latitude). You may have found it helpful to define a function to create the linear regression plots.

Next, created a series of scatter plots and included the linear regression line, the model's formula, and the r² values. The following plots were generated:

- Northern Hemisphere: Temperature vs. Latitude
  ![image](https://github.com/user-attachments/assets/9439c0ed-943b-4604-a57d-72c233db3aea)
  
- Southern Hemisphere: Temperature vs. Latitude
  ![image](https://github.com/user-attachments/assets/2868be09-c383-421e-8b76-91b801b4eef4)

- Northern Hemisphere: Humidity vs. Latitude
  ![image](https://github.com/user-attachments/assets/7c1b15c3-07f9-4bb3-9506-8e8bccb0999b)

- Southern Hemisphere: Humidity vs. Latitude  
  ![image](https://github.com/user-attachments/assets/698fb54d-2101-438e-ab48-f33df8324ad2)

- Northern Hemisphere: Cloudiness vs. Latitude
  ![image](https://github.com/user-attachments/assets/fe27f043-b9c3-469c-86e5-c051ef75ff00)  

- Southern Hemisphere: Cloudiness vs. Latitude
  ![image](https://github.com/user-attachments/assets/0575687e-d870-4c6d-bc79-a0a0c204b946)
  
- Northern Hemisphere: Wind Speed vs. Latitude
  ![image](https://github.com/user-attachments/assets/022e7109-e9a2-4eb5-bdfe-9c194d7f9e71)
  ![image](https://github.com/user-attachments/assets/f8a94426-2d85-4784-92e9-215e54c9930f)  

- Southern Hemisphere: Wind Speed vs. Latitude
  ![image](https://github.com/user-attachments/assets/80fff588-04bd-4420-b4ee-97caaf086a00)

After each pair of plots,  explained what the linear regression was modeling, described any relationships noticed, and highlighted other findings you uncovered.


# Part 2: VacationPy

### In this deliverable, weather data skills were used to plan future vacations. Additionally, Jupyter notebooks, the geoViews Python library, and the Geoapify API were utilized. applied weather data insights to plan vacations using map visualizations.

### tasks included:

## 1. Creating Map Visualizations: 
Using the geoViews Python library and the Geoapify API, you created a map that displayed points for each city, with point size representing humidity levels.

## 2. Finding Ideal Vacation Locations: 
By filtering the data to meet specific weather criteria (e.g., temperatures between 21-27°C, wind speeds less than 4.5 m/s, and zero cloudiness), you identified cities with ideal weather conditions.

## 3. Locating Hotels: 
A new DataFrame, hotel_df, was created to store city details and humidity. The Geoapify API was used to locate hotels within 10,000 meters of each city’s coordinates, with additional information on hotel names and countries added to the map’s hover messages.

### This project provided a comprehensive approach to analyzing weather data and applying it to practical vacation planning scenarios.

The code needed to import the required libraries and load the CSV file containing the weather and coordinates data for each city created in Part 1 was provided to help get started.
![image](https://github.com/user-attachments/assets/0172b20d-890a-4788-8739-60a88f9b936c)

The main tasks involved using the Geoapify API, the geoViews Python library, and Python skills to create map visualizations.  
To complete this part of the assignment, the VacationPy.ipynb starter code was opened and the following steps were followed:
![image](https://github.com/user-attachments/assets/682f3406-087a-4602-9075-5ca8249963cb)

  
- A map was created, displaying a point for every city in the city_data_df DataFrame, where the size of the point represented the humidity in each city.
![image](https://github.com/user-attachments/assets/e6067a73-9174-4fe3-8c49-b807ca71ffb1)

- The city_data_df DataFrame was narrowed down to find ideal weather conditions. For example:
    - A maximum temperature lower than 27 degrees but higher than 21 degrees
    - Wind speed less than 4.5 m/s
    - Zero cloudiness
![image](https://github.com/user-attachments/assets/26791ebe-461c-4a97-9f6a-b981e4229b6b)
![image](https://github.com/user-attachments/assets/56d0f2a6-9f07-4300-97e9-47ac44208ebc)


  (Specifications could be adjusted, but a reasonable limit was ensured on the number of rows returned by API requests.)

- A new DataFrame called hotel_df was created to store the city, country, coordinates, and humidity.
  ![image](https://github.com/user-attachments/assets/39df5757-d133-49b5-b563-22fb004cc51e)
  ![image](https://github.com/user-attachments/assets/e8f44f02-ba5d-4dd4-80ef-9efcd061fa0e)
  ![image](https://github.com/user-attachments/assets/31365d31-e9d2-4b20-beda-2304ddd47ed8)
  
- For each city, the Geoapify API was used to find the first hotel located within 10,000 meters of the coordinates.
  ![image](https://github.com/user-attachments/assets/24757cfb-6423-4b32-a7ea-3821455e3e30)
    
- The hotel name and the country were added as additional information in the hover message for each city on the map.
-   ![image](https://github.com/user-attachments/assets/775981dd-09c2-4f25-80a4-dae65165ca58)

  # Project Setup and Configuration
 
### Organized Files: In local repository, created a new directory for this assignment, named WeatherPy. Inside this directory, you placed the following files from the 
### provided starter code ZIP file: api_keys.py, WeatherPy.ipynb, and VacationPy.ipynb.
### Added a .gitignore File: To prevent sensitive files like api_keys.py from being shared publicly, you created a .gitignore file in your repository. This file included:arduino

# Adding config.py file.
### api_keys.py (ADDED to git.ignore)
Committed Your Changes: used the command git status to review untracked files. added the .gitignore, WeatherPy.ipynb, and VacationPy.ipynb files using git add, then committed and pushed changes. ensured that only WeatherPy.ipynb and VacationPy.ipynb were visible on GitHub, keeping api_keys.py private.







