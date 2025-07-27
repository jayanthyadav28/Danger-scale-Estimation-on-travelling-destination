# Danger-scale-Estimation-on-travelling-destination

This is a simple Flask web application that estimates avalanche risk based on user-provided parameters like location, time of year, activity type, elevation, and group size.

## 🚀 Features

- User-friendly form to collect details such as:
  - Mountain massif
  - Month of the year
  - Type of activity
  - Number of travel mates
  - Elevation
- Calculates an **avalanche index** based on weighted rules
- Displays a summary and risk score to the user

## 🧮 How the Index is Calculated

The `make_aval_index` function uses the following input data to compute a score:

- Massif (region)
- Month
- Activity type
- Group size
- Elevation


