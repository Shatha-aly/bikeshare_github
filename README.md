>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Date created
19 Feb 2025

### Project Title
Bikeshare Project 

# Bikeshare Data Analysis Script

## Overview
This script is designed to analyze US bikeshare data for three major cities: **Chicago, New York City, and Washington**. It provides various insights, including statistics on travel times, stations, trip durations, and user demographics. The script allows users to filter data by city, month, and day of the week.

## Prerequisites
Ensure that you have the required dependencies installed:

- Python 3.x
- Pandas
- NumPy

You also need the bikeshare CSV datasets in the same directory:
- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`

### Description
Describe what your project is about and what it does

## Script Structure

### `get_filters()`
- Prompts the user to enter:
  - The city to analyze (**Chicago, New York City, Washington**).
  - The month to filter by (**January to June**) or **"all"** for no filter.
  - The day of the week to filter by (**Monday to Sunday**) or **"all"** for no filter.
- Returns the selected filters.

### `load_data(city, month, day)`
- Loads the appropriate city data.
- Filters the dataset based on user input for month and day.
- Returns a filtered **Pandas DataFrame**.

### `time_stats(df)`
- Computes and displays:
  - The most common month for bike trips.
  - The most common day of the week for bike trips.
  - The most common start hour for trips.

### `station_stats(df)`
- Computes and displays:
  - The most commonly used start station.
  - The most commonly used end station.
  - The most frequent combination of start and end stations.

### `trip_duration_stats(df)`
- Computes and displays:
  - The total travel time of all recorded trips.
  - The average trip duration.

### `user_stats(df)`
- Computes and displays:
  - The count of different user types.
  - The count of gender (if available in the dataset).
  - The earliest, most recent, and most common birth year (if available in the dataset).

### `main()`
- Runs the script in a loop to allow users to restart the analysis with new inputs.

### Files used
Include the files used

### Credits
It's important to give proper credit. Add links to any repo that inspired you or blogposts you consulted.



