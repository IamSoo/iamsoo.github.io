---
layout: posts
title:  "Web scrapping with python & beautifulsoup"
date:   2019-11-24 12:44:05 -0500
categories: Web Scrapping with Python beautifulsoup
author: Soo
#img: elk-logo.png 
---
Web scrapping is normally done by a web crawler or a bot to extract information from the web page directly.
Normally the html content is parsed and then formatted according to the requirement. Then the formatted output is 
saved in db or used by other services for analysis.
  
Is web scrapping illegal?
    Many big companies do this. Even google does this through its Googlebot. https://support.google.com/webmasters/answer/182072
But it creates unexpected load on the site that may hamper its business. So Facebook has made a list of guidelines,
mentioned here : https://www.facebook.com/apps/site_scraping_tos_terms.php . So technically companies can take legal 
action against you.

I have written a python application that uses beautifulsoup to scrape a hackernews site for development purpose.
The application is also wrapped in container and can be used as a microservice. The app takes one parameter i.e no of posts
and return that many no of posts order by rank.

The github link is here for reference of code : https://github.com/IamSoo/hackernews-scraper

##### Enjoy


=== Thank you ===

