
## ANALYSIS Of MTA Turnstile data New York CITY

The world is experiencing a once-in-a-lifetime pandemic that necessitates controlling and limiting the capacity in public and crowded places. As a CDC (Centers of Disease Control and Prevention) We keep preserving the health and safety of citizens and residents from the risk of the spread of novel coronavirus. Our task was to use New York City MTA Turnstile data and cooperation with Ministry of Health to avoid crowds place and to provide people with vaccination centers and provide enough space in each station.


## Design

This study originated by CDC company to maximize protection from the COVID-19 and prevent possibly spreading it to others based on MTA subway data from the New York City Public Transportation Authority (MTA). The MTA turnstile data for the New York subway is a series of data files that contain the cumulative number of entrances and exits by station, turnstile, date and time. Data files are produced weekly, data logs are typically collected every 4 hours with some exceptions.


## Data

 The dataset have been used is the turnstile dataset which contains around 3M rows and 11 columns. Most notable columns include: entries, stations, C/A, unit and scp. 
 
## Algorithms

Exploratory Data Analysis was done to MTA Turnstile Dataset:
- Processing of MTA turnstile data for the four months (Septemper , October, November, December) for use in stations state analysis.
- Clean and pre-process data by renaming columns, adding calculated fields, removing erroneous data, and grouping by station and date.
- Finding the busiest day in a week and the busiest hour in day in each stations.
- Displaying the results obtained in the form of graphical charts.

## Tools

- Numpy
- Pandas
- Matplotlib
- Seaborn
- SqlAlchemy
- Jupyter

