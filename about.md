---
layout: page
title: About
---

## Project

This is a digital humanities project centered around Facebook advertisements purchased by the Internet Research Agency, a Russian "troll farm." In this project, I seek to visualize data in a few different ways: geographically, graphically, and chronologically. 

I do this to ask a few questions of these ads. Like many Americans, I've heard about Russian disinformation from the news and government, but before this project, I did not know about it in much detail. I wanted to learn more about the ads, and what the Internet Research Agency intended to do with them. 

I had a few specific questions:

1. Where are these ads targeted, geographically? What does it mean?
2. When were these ads purchased? Do they coincide with specific points in the presidential election?
3. What kind of rhetoric do these ads use? 

In doing this project, I discovered a few different things. I will describe these findings in more detail on their respective pages, but here's what I found:

1. Ads are targeted to a combination of large cities, cities in important swing states, and cities that have large Black and immigrant populations.
2. 
3. These ads use highly polarized rhetoric from both sides of the political spectrum, and are sometimes written using language that specifically reference internet culture.

To learn more about these points, head to their pages ([maps](https://isawil.github.io/russian-ads/maps), [rhetoric](https://isawil.github.io/russian-ads/memes), [time](https://isawil.github.io/russian-ads/time)).

## Dataset

This dataset was compiled by the University of Maryland, and is available [here](https://mith.umd.edu/irads/data/).

I cleaned the data using OpenRefine and Google Sheets. While cleaning, I realized I would need to have two different spreadsheets in order to visualize the data most effectively. I created one spreadsheet for my maps, and one for my graphs. 

For my map spreadsheet, I created a new row for each location, even if it duplicates the ad. To clarify, here's what happened:

(image of "dirty" location data)

As you can see, all of the geographic data for each ad was collected in one cell per ad. This made it impossible to visualize with Tableau. Using OpenRefine, I separated these multi-valued cells by the separator--in this case, the "|" symbol. This created one new row per location. Because OpenRefine's "fill down" option was impractical for my uses (explain), I exported the OpenRefine spreadsheet as a CSV and imported it to Google Sheets. From there, I manually filled down the new, empty rows with information from their completed sibling. 

For my 

I visualized the data using Tableau and Timeline.js. 

## Me

My name is Isaac Williams. I'm a graduate student at UCLA, where I study library and information science. I created this project for Miriam Posner's Digital Humanities 201 class. You can learn more about me [here](https://isawil.github.io).
