# Data-Visulization-in-Dimple

This repositry helps us to understand how to develop a Data Visulization and make it interactive using Dimple.js
we have world_cup.tsv, the tab separated values. Contains data related to football world cup matches. It contains colums like attendance, team1,team2, goals, year, time, stadium etc etc.
Let us plot a chart between attendance vs year.
we need to sum all the attendance for a given year before plotting.
Let us take year over x-axis and attendance over y-axis.
Since the x-axis is a continuous variable and it is over time. the best graph will be line chart.
But let us plot first a bar chart and than later plot a scatter plot and then finally plot the line chart.
Dimple.js is a library build on top of D3 provide an abstract over D3, which will be easy to work on and build with less code.
less code means less error prone.
It provide a gentle learning curve.
Exposes D3 objects, so that we can enhance.

For the html provided to view interactive mode.
you need to install python.
Start the server in command line where your project folder is available as python -m http.server.
server will start and the url is http://0.0.0.0:8000/
go to your browser and type http://0.0.0.0:8000/basic_charts.html

you can now see a bar chart. 
