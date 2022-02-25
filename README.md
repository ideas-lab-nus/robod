## General Information

This repository contains the data files and relevant analysis code for ROBOD, Room-level Occupancy and Building Operation Dataset.

Data collection period: 2021–09-07 00:00 to 2021-12-23 23:55

Each data measurement contains the timestamp information corresponding to the time when the data measurement was recorded and followed the date-time format: YYYY-MM-DD HH:MM +08:00. 
The last component (i.e., +08:00) indicates a UTC offset of +8 hours as the data collection was conducted in the tropical island of Singapore. 
All data measurements followed a sampling interval of 5 minutes.
In total, 181 days of data was collected from the School of Design and Environment 4 (SDE4) building located at the National University of Singapore.

Each folder in the existing version of the dataset is named based on the following format: combined_Room\<Room Number\>.csv

| File               | Description                                                       |
|--------------------|-------------------------------------------------------------------|
| combined_Room1.csv | All data categories combined for Room 1 (Lecture Room) - 29 days  |
| combined_Room2.csv | All data categories combined for Room 2 (Lecture Room) - 29 days  |
| combined_Room3.csv | All data categories combined for Room 3 (Office Space) - 29 days  |
| combined_Room4.csv | All data categories combined for Room 4 (Office Space) - 47 days  |
| combined_Room5.csv | All data categories combined for Room 5 (Library Space) - 47 days |


## Room Description

<img src="./room_descriptions.png">

## Data Categories Description

<img src="./sensor_descriptions.png">