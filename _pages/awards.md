---
layout: archive
title: "Honors & Awards"
permalink: /awards/
author_profile: true
redirect_from:
  - /resume
---

{<!DOCTYPE html>
<html>
<head>
  <title>Achievements in Competitions</title>
  <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
  <style>
    #chart {
      width: 600px;
      height: 400px;
      margin: 0 auto;
    }
  </style>
</head>
<body>
  <div id="chart"></div>

  <script>
    // Data for ML hackathons, national idea competitions, and robotics competitions
    var competitions = ['ML Hackathons', 'National Idea Competitions', 'Robotics Competitions'];
    var wins = [3, 2, 4]; // Number of wins

    // Creating the trace
    var trace = {
      x: competitions,
      y: wins,
      type: 'bar',
      marker: {
        color: ['#FF6F61', '#6B5B95', '#88B04B']
      }
    };

    // Creating the data array
    var data = [trace];

    // Creating the layout
    var layout = {
      title: 'Achievements in Competitions',
      xaxis: {
        title: 'Competition Type'
      },
      yaxis: {
        title: 'Number of Wins'
      }
    };

    // Creating the plot
    Plotly.newPlot('chart', data, layout);
  </script>
</body>
</html>
