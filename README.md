# COVID-19-Dashboard-Germany
A dashboard which displays current and historical stats about the COVID-19 pandemic in Germany. <br>
This app is hosted at https://covid-dashboard-ortgies.herokuapp.com/
<br>
To accumulate hosting limits on heroku, the app is split into two parts: <br>
data_prep.ipynb contains the code for the data collection and processing. The code is executed daily to update the COVID statistics. <br>
dash.ipynb contains the UI code. This file is hosted on heroku. <br>
