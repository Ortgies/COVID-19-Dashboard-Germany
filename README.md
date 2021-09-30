# COVID-19-Dashboard-Germany
A dashboard which displays current and historical stats about the COVID-19 pandemic in Germany. <br>
This app is hosted at https://covid-dashboard-ortgies.herokuapp.com/
<br>
![Screenshot](https://github.com/Ortgies/COVID-19-Dashboard-Germany/blob/main/Assets/screenshot.png)

# Motivation
Web design is not one my biggest talents. I have quite a bit of experience with UI design for mobile apps in Flutter/Dart, but the data science field is still dominated by web dashboards. <br>
For this reason I wanted to try out Dash and also refresh my knowledge in HTML. <br>
I chose the Covid pandemic as the subject of my dashboard, since there is a large amount of openly available data which can be transformed to numerous interesting statistics. <br>

# Data collection
Raw covid data is retrieved ArcGIS and the Robert Koch Institute (RKI). <br>
Geolocations are sourced from opendatalab. <br>
Population statistics are collected from the Statistisches Bundesamt. <br>

# Application
The web application is based on Dash and hosted on Heroku. <br>
Raw covid data is transformed and displayed in a number of different graphics:
- sunburst chart showing current cases by state and district
- map showing current incidence by state and district
- overview table for states and districts
- line chart showing incidence over time
- bar chart showing R value over time
- line chart showing mortality over time
- nightingale graph showing cases and mortality per month
- line chart showing cases by age
- percentage chart showing cases by age
- bar chart showing cases by gender
