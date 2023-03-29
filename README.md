# Python-API-Challenge

# Part 1: WeatherPy

A Python script was used to visualize the weather of 500+ cities of varying distance from the equator. I'll use the [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and my problem-solving skills were used to create a representative model of weather across cities.

## Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude:

To fulfill the first requirement, I'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I'll create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude.
* Humidity (%) vs. Latitude.
* Cloudiness (%) vs. Latitude.
* Wind Speed (mph) vs. Latitude.

## Requirement 2: Compute Linear Regression for Each Relationship:

To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

* Northern Hemisphere - Temperature (F) vs. Latitude.
* Southern Hemisphere - Temperature (F) vs. Latitude.
* Northern Hemisphere - Humidity (%) vs. Latitude.
* Southern Hemisphere - Humidity (%) vs. Latitude.
* Northern Hemisphere - Cloudiness (%) vs. Latitude.
* Southern Hemisphere - Cloudiness (%) vs. Latitude.
* Northern Hemisphere - Wind Speed (mph) vs. Latitude.
* Southern Hemisphere - Wind Speed (mph) vs. Latitude.

## WeatherPy

**Latitude Vs. Temperature**

  ![image](https://user-images.githubusercontent.com/120751287/228456198-d5b3caf8-0c83-428f-bfe5-cab5065e1e3f.png)
  
  ![image](https://user-images.githubusercontent.com/120751287/228457339-10e1446c-dfa3-456f-ba7f-c63d3f949afb.png)
  
  ![image](https://user-images.githubusercontent.com/120751287/228457398-23335a69-9684-46ea-ac33-bf776565c01a.png)

**Humidity vs. Latitude**

  ![image](https://user-images.githubusercontent.com/120751287/228457557-a0cc7627-3361-478f-929f-fc0a1cacca27.png)

  ![image](https://user-images.githubusercontent.com/120751287/228457650-cf6fa91f-0a1c-4eca-93ee-ffce98bc627a.png)

  ![image](https://user-images.githubusercontent.com/120751287/228457695-88bba9ed-801c-4b29-b31d-ed917534f9ac.png)

**Cloudiness vs. Latitude**

  ![image](https://user-images.githubusercontent.com/120751287/228457796-5b233a46-28df-44e3-85e2-4ba5db5ebd9f.png)

  ![image](https://user-images.githubusercontent.com/120751287/228457920-c9c3dcec-2c79-4374-86c9-42720f879bea.png)
  
  ![image](https://user-images.githubusercontent.com/120751287/228457954-d81de9a1-83fa-4237-a322-b5561b5ec4ee.png)

**Wind Speed vs. Latitude**

  ![image](https://user-images.githubusercontent.com/120751287/228458100-34686d14-307f-40b0-b57a-e946293ea0e3.png)
  
  ![image](https://user-images.githubusercontent.com/120751287/228458183-21511cac-022f-4919-af6f-83e34e7067ca.png)
  
  ![image](https://user-images.githubusercontent.com/120751287/228458212-5029cc78-bb3c-423d-8651-80e84f8acfce.png)

### Part 2: VacationPy

Jupyter notebooks, the geoViews Python library, and the Geoapify API were used to work with weather data to plan future vacations.

  ![map_plot](https://user-images.githubusercontent.com/120751287/228461516-bf0726a6-273d-4422-aba0-3d6b84c80768.png)

* Narrow down cities to find my ideal weather condition, the criteria are listed below:
  1. A max temperature lower than 27 degrees but higher than 21.
  2. Wind speed less than 4.5 m/s.
  3. Zero cloudiness.
  
* Create a new DataFrame called `hotel_df` to store the `City`, `Country`, `Coordinates` and `Humidity`. Also, add the `Hotel Name` and "Country" as additional information in the hover message for each city in `hotel map'.

  ![map_plot](https://user-images.githubusercontent.com/120751287/228464703-87e865d7-cd57-4f35-9757-3bb4fdb7740d.png)

* Add the hotel name and the country as additional information in the hover message for each city in `hotel map`.
  
  ![Hotel_Map](https://user-images.githubusercontent.com/120751287/228464829-543e492d-301d-4ad9-8441-3e3387d90518.png)
