---
layout: page
title: About
---

## Project

This is a digital humanities project centered around Facebook advertisements purchased by the Internet Research Agency, a Russian "troll farm." In this project, I seek to visualize data in a few different ways: geographically, graphically, and chronologically. 

## Dataset

This dataset was compiled by the University of Maryland.

I cleaned the data using OpenRefine and Google Sheets. While cleaning, I realized I would need to have two different spreadsheets in order to visualize the data most effectively. I created one spreadsheet for my maps, and one for my graphs. 

For my map spreadsheet, I created a new row for each location, even if it duplicates the ad. To clarify, here's what happened:

[image of "dirty" location data]

As you can see, all of the geographic data for each ad was collected in one cell per ad. This made it impossible to visualize with Tableau. Using OpenRefine, I separated these multi-valued cells by the separator--in this case, the "|" symbol. This created one new row per location. Because OpenRefine's "fill down" option was impractical for my uses (explain), I exported the OpenRefine spreadsheet as a CSV and imported it to Google Sheets. From there, I manually filled down the new, empty rows with information from their completed sibling. 

I visualized the data using Tableau and Timeline.js. 

## Me

My name is Isaac Williams. I'm a graduate student at UCLA, where I study library and information science. I created this project for Miriam Posner's Digital Humanities 201 class. You can learn more about me [here](https://isawil.github.io).
