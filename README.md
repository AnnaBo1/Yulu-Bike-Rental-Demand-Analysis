# Yulu-Bike-Rental-Demand-Analysis

Yulu is a leading micromobility provider in India, offering shared electric bikes for daily commutes to ease traffic congestion and provide a safe, convenient, and affordable transportation solution. The company has strategically placed bike-sharing stations in optimal locations, including metro stations, bus stops, office spaces, residential areas, and corporate offices, to facilitate first and last-mile commutes.
The goal is to identify key factors that could help improve service and increase bike rentals.

## **Dataset Description**

The **Yulu** dataset contains detailed information about the demand for shared electric bikes over time. The dataset includes hourly rental data from 2011 to 2020, featuring various attributes that can help analyze demand trends and patterns.

### **Dataset Columns**

- **datetime**: Date and time of data collection, recorded hourly.
- **season**: Season of the year (1: Spring, 2: Summer, 3: Autumn, 4: Winter).
- **holiday**: Whether the day is a holiday (extracted from the holiday schedule).
- **workingday**: Indicates if the day is a working day (1) or a non-working day (0) (i.e., weekends or holidays).
- **weather**: Weather conditions:
  - Clear, Partly Cloudy, Mostly Cloudy
  - Fog + Cloudy, Fog + Scattered Clouds, Fog
  - Light Snow, Light Rain + Thunderstorm + Scattered Clouds, Light Rain + Scattered Clouds
  - Heavy Rain + Hail + Thunderstorm + Fog, Snow + Fog
- **temp**: Temperature in Celsius.
- **atemp**: "Feels like" temperature in Celsius.
- **humidity**: Humidity percentage.
- **windspeed**: Wind speed in km/h.
- **casual**: Number of casual (non-registered) users.
- **registered**: Number of registered users.
- **count**: Total number of bikes rented, including both casual and registered users.

## **Objective**

The primary objective of this analysis is to identify the factors that drive demand for shared bikes in India. By analyzing the data, we aim to provide actionable insights for Yulu to help them increase the number of rentals and improve the efficiency of their bike-sharing service.

### **Key Analysis Areas**

- Trends in bike rentals over time
- Impact of weather conditions on bike rentals
- Seasonal and holiday patterns in demand
- The effect of temperature and humidity on bike rentals
- Impact of working days vs holidays on demand

## **Technologies Used**

- **Python** (for data manipulation and analysis)
- **Pandas** (for data processing)
- **Matplotlib** and **Seaborn** (for data visualization)


## **Conclusion**

This project provides valuable insights into the factors influencing bike rental demand and can guide Yulu in improving their services. The analysis aims to optimize bike usage based on weather patterns, seasons, and working conditions, ultimately helping to boost the company's revenue.
