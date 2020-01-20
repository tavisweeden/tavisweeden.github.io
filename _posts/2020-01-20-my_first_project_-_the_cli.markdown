---
layout: post
title:      "My First Project - the CLI!"
date:       2020-01-20 16:50:58 -0500
permalink:  my_first_project_-_the_cli
---


Making my first application was a daunting and often frustrating adventure, punctuated by many episodes of blank, mindless staring. If you are also new to the web development world, this admission may remind you of some of your own experiences. 

The Command Line Interface Project gives students an opportunity to test what they’ve learned in the program thus far. Theory is put into action and we learn a lot in the process.

The first and foremost challenge I faced was learning to use a public API to fetch data from. I chose an API as opposed to scraping after being urged to by our cohort lead. Apparently, many students in her last cohort had experienced application errors due to the webpages they scraped having changed. I thought it was a prudent idea and set forth finding a suitable API. 

I selected an API that didn’t require a key to make requests; just to simplify the process. My API provided users access to a database to information relating to the Star Wars films. I opted to create an application that would allow a user to select a particular Star Wars character, and would return a list basic data for that character. 

As there are no lessons on using API’s in the Flatiron curriculum, I had to rely on the available videos and the internet when learning how to use the API data in my program. I was eventually able to query the API and have data in the form of JSON returned to my application. The data contained all of the characters and their attributes. I created a method to iterate over this data, which was essentially a hash, and stored it in an object that sorted it by attribute type. 

However, I was having difficulty isolating the data for each individual character, and getting that data printed to the terminal. My breakthrough came when I studied the API documentation, and found the search function. The search function allows you to isolate particular data on the site. In my case, I was able to search individual characters, which would return their attributes. I refactored my API query method to search individual characters, and used the same iteration to put the returned attributes into an object.

After that, the process was fairly simple. I made a method to allow the user to type a character name, which would return a list of the character’s attributes. Because of the flexibility of the API search function, the user could type partial names, and didn’t have to worry about case-sensitivity. 

In the future I could use my existing code as a template and create options to access all of the data on the Star Wars API site. 

In retrospect, I realize I still have A LOT to learn about objects and iteration and the use and dependencies of classes. BUT, it was a good learning experience; stretching me and making me push through a lot of doubt and vexation. 

