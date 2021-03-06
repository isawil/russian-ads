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

The ultimate conclusion I arrived at is that the Internet Research Agency was aware of specific tensions or areas of concern in American politics, and deliberately exploited them through social media-based ads. Users' ability to curate audiences for their Facebook ads means that the IRA was able to also exploit these lax rules and deliver targeted propaganda to American Facebook users.

To learn more about my conclusions, head to their pages ([maps](https://isawil.github.io/russian-ads/maps), [rhetoric](https://isawil.github.io/russian-ads/rhetoric), [time](https://isawil.github.io/russian-ads/time)).

## Cleaning

While creating this project, I learned a lot from cleaning and visualizing data. In some ways, I would say I learned more from cleaning the data than I did from visualizing it. Cleaning the data took a long time. The dataset is robust, but it was not created for my purposes--it was created for use at the University of Maryland. Because of this, I had to clean the data so it would be most useful for me. 

In cleaning the data, I realized rather slowly that I would need to create multiple spreadsheets: one for visualizations based off interests alone, and one for maps and other visualizations. This is due to the way that the data is structured. In its original form, interests are separated by pipes, as are locations (if multiple) and languages. I could not find a way to create a single spreadsheet that would also work for the many different types of visualizations if I wanted to create. 

It took me a long time to clean everything, but it served a purpose beyond the obvious. To clean the data, I had to become very familiar with it in a way I would not have if I had used a dataset that was ready to go. As I used OpenRefine and Google Sheets, I saw how many times Abeline, Texas appeared in the data. I saw how many ads referenced police violence, either opposing it, or supporting the police force. I saw how many rubles were spent on ads, how many ads were at least partially in Arabic, and how many people clicked on the ads. There are about 3,500 ads in this dataset, and it is highly unlikely that I would have been able to know all of what I know now from simply organizing the ads in Tableau--or if I had computationally cleaned the spreadsheet. 

Cleaning was, for me and many other people, tedious and sometimes frustrating. I spent many hours cleaning the dataset because I knew that once I had it formatted the way I wanted, visualizing it would be much easier. Many times I wanted to press a button that would clean the dataset the way I wanted to. While I would not want to clean this again, I do know that doing so--and getting my hands “dirty” in the process--was imperative to learning more about the datset.

## Visualization

I visualized the data using Tableau Public. I decided to do this to explore the variety of visualizations available on Tableau. When I had finished cleaning the spreadsheet, I linked it to Tableau and created a variety of visualizations just based off what was in my spreadsheet. 

## Constraints

This dataset comes from the IRAds website, created by the University of Maryland. The dataset was manually coded by 160 students enrolled in classes at the university. However, the original dataset comes from a dataset Facebook released to Congress in 2018. The House Intelligence Committee made these ads public in 2018, and that data can be found [here](https://intelligence.house.gov/social-media-content/social-media-advertisements.htm). 

There are some constraints to the dataset. While it contains approximately 3,500 posts, [it does not contain](https://www.recode.net/2018/5/10/17339864/congress-russia-advertisements-facebook-donald-trump-president) any “organic” content, or content created by the IRA, that they did not pay to promote. According to the House Intelligence Committee, there are around 80,000 organic posts that were not included. 

Another constraint of the dataset is that many of these ads are at least partially written in Arabic, whether in the post text, or the page name. These ads were also processed from their original PDF forms, and as a result, text written in Arabic returns as numbers--usually 7s. Because I do not feel confident enough in my Arabic to correct mistakes, or to transliterate text, I did not correct these mistakes. That is one way this project could be improved.

## Me

My name is Isaac Williams. I'm a graduate student at UCLA, where I study library and information science with a concentration in informatics. I created this project for Miriam Posner's Digital Humanities 201 class. You can learn more about me [here](https://isawil.github.io).
