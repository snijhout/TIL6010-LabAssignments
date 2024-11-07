# CO2-emissions folder
The main file is Travel-statistics.ipynb, and from here are code can be run/output can be generated

At the beginning of each block of code a short explanation is given. It is also indicated if a path needs to be changed.

The first block of code takes long (10 min) as the data needs to be retrieved from the server

Libraries that need to be installed are in requirements.txt so that geopy and pandas etc, are included. (Install these in the TIL6022 environment/kernel)

The main goal is to retrieve information for all flights from the netherlands, and therewith look at distances, CO2 emissions, flight times. Furthermore, a comparison is also made by comparing the flight data with travel data for the remaining transport modes.

Steps in the file are:
- retrieve flight data and coordinates
- calculate distances emissions and flight times (based on 2024 quarter 2, because this is what we previously had in mind)
- generate charts and graphs
- process flight data for 2022 specifically (chosen because availability of data etc)
- show data 2022

