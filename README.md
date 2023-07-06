# Climate-Clash
An extensive analysis that aims to identify the specific climatic factors in VIT Bhopal responsible for causing my medical issues by analyzing and comparing the climatic data of VIT Bhopal with my hometown (Kottayam, Kerala).

## Project Link
[Dashboard Link](https://public.tableau.com/views/ClimateClash/Analysis?:language=en-US&:display_count=n&:origin=viz_share_link)

## Screenshots

### Analysis
![image](https://github.com/Pritosh4/Climate-Clash/assets/93176385/26e494d9-2708-4809-a9c5-fcc999fb0842)

### Dashboard
![image](https://github.com/Pritosh4/Climate-Clash/assets/93176385/4436165c-56b3-4ef5-ae53-a4c730c7c4fd)

![image](https://github.com/Pritosh4/Climate-Clash/assets/93176385/0ed7e8fa-abca-4132-8e54-6edb138f629e)

## Inspiration
After I started coming to college, I noticed a pattern wherein I would quickly fall sick and it would take me around three days to recover each time I came back to campus from home. This observation sparked my curiosity, and I decided to investigate the possible reasons behind my recurrent sickness. I decided to analyse the climatic data of my college and compare it to the weather conditions back home.

## Process
To begin my analysis, I collected data on various weather parameters such as temperature, humidity, precipitation, wind speed, etc for both locations. I obtained historical weather data for the corresponding periods of time when I was sick over a span of 12 months.
I loaded the data into a `PostgreSQL` database and analysed this data using `SQL` queries to answer questions such as:
- When was the hottest day on campus?
- When was the hottest day at home?
- What was the temperature when one of the two places was experiencing its hottest day?
- When was the coldest day on campus?
- When was the coldest day at home?
- What was the average temperature of each month?
  
After answering these questions, I visualized this data, using Tableau, in multiple ways to gain the necessary insights required to reach a detailed answer.

## Reflection
After looking at all the parameters I was able to understand that, though the varying temperature did play a role but, the main reason behind my sickness was actually the humidity and the wind speed. The difference in the wind speed and humidity between the 2 places was  more significant and more influential on my health as compared to the temperature.
