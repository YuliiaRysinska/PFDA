# PFDA
#### PFDA repository includes my_work, assignments and project that focus on the acquired knowledge and skills in PROGRAMMING FOR DATA ANALYTICS course at ATU, lecturer Andrew Beatty (https://github.com/andrewbeattycourseware/PFDA-courseware.git)

## Purpose of PFDA: 
#### 1)Programmatically create plots and other visual outputs from data.
#### 2)Design computer algorithms to solve numerical problems.
#### 3)Create software that incorporates and utilises standard numerical libraries.
#### 4)Employ appropriate data structures when programming for data-intensive applications.

# Assignment 2 weather
#### Jupyter notebook called assignment2-weather.ipynb that has a nice plot of the temperature over time( "dryBulbTemperature_Celsius" ). 

# Assignment 3 domains
#### Notebook called assignment03-pie.ipynb have a nice pie chart of peoples email domains in the csv file at the url https://drive.google.com/uc?id=1AWPf-pJodJKeHsARQK_RHiNsE8fjPCVK&export=download. This csv file has 1000 people. You may download the data or link to it.

# Assignment 5
#### Notebook called assignment_5_risk.ipynb simulates 1000 individual battle rounds in Risk (3 attacker vs 2 defender) and plots the result. One battle round is one shake of the attacker and defender dice.
#### Rules of Risk: In Risk one army fights another. (using 6 sided dice). In each battle round, the attacker can put forward up to three of their troops (3 dice).The defender can use up to two of their defending troops (2 dice).Each side looses troops depending on the following rules:The two top dice dice are compared (ie the attackers top dice roll with the defenders top dice roll).If the attackers dice is the same or lower they loose one troop otherwise the defender looses a troop (ie if the attackers dice is higher). The next two highest dice from each side are then compared (ie the attackers second highest to the defenders second highest). If the attackers dice is the same or lower they loose one troop otherwise the defender looses a troop (ie if the attackers dice is higher)

# Assignment 6 (Knock airport Weather)
#### Create a python file or notebook called assignment_6_Weather (.py or .ipynb). Get the data from this link: https://cli.fusio.net/cli/climate_data/webdata/hly4935.csv. Create Plots:1)The temperature, 2) mean temperature each day. 3) mean temperature for each month, 4)Windspeed (there is data missing from this column),5) rolling windspeed (say over 24 hours),6) max windspeed for each day,7) monthly mean of the daily max windspeeds

# Project

#### Link to video description: https://atlantictu-my.sharepoint.com/:v:/g/personal/andrew_beatty_atu_ie/EXcFP34yMEFHqBdthedbDMcBoRx0r3owJlNSTZYl1ICSVg?e=GdeX7U&nav=eyJwbGF5YmFja09wdGlvbnMiOnt9LCJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJUZWFtcyIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJwb3N0cm9sbC1jb3B5bGluayIsInJlZmVycmFsUGxheWJhY2tTZXNzaW9uSWQiOiJkOGRhODQ0Ni0xN2M1LTQ0MDMtYjI2Yy1jMDY4NTk5ZWQ2ZmMifX0%3D

## Description:
#### Notebook project_pfda demonstrates performing data analysis on data of wind speed around the country with a view to windfarm from https://www.met.ie/climate/available-data/historical-data vebsite.

#### Steps: 1) download a CSV file with mean wind speed from Shannon airoport location from 01 January 1990.2) clean and normalize the data 3) make analysis

#### • Questions you can ask: How much wind power is there at a particular location?This is quite open ended, is this just the mean wind speed for an hour/day/month/year, or should you take into account that there are wind ranges that the windfarms can operate in. (minmax speeds) ▪ Some analysis of what power when would be useful (time of day/year) o Are the wind speeds likely to be the same in 10 years in the future? ie is there a trend in recorded wind speeds over the last few decades. o Is there any other weather metric worth analyzing (eg rain, temp) o What will the power output of the windfarms in Ireland be like next week, according to the weather forecasts? (ok that is a tricky one, because you would need to get, or make up, information about the size and locations of the wind farms in Ireland, one find/makeup the windspeed to power output equation.



