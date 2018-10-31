# 9ja-musicians-wiki-ranklist
A personal project that gets the list of Nigerian musicians, ranks them in descending order by their Wikipedia page views and displays it on a simply styled HTML Page.

This inspiration for this project was gotten from [this tutorial on python web scrapping](https://realpython.com/python-web-scraping-practical-introduction/) by Colin OKeefe on Real Python.com where python was used to retreive a list of 5 most popular mathematicians. 

This project attempts to use API calls to the MediaWiki API as well as some client side web scraping using the fecth api and the DOM parser to recreate something similar for a Nigerian Musicians Case Study

This page uses the MediaWiki API to obtain the list of musicians in Nigeria on the wiki page about Nigerian musicians and uses WikiMedia's XTool to get the details about each individual musicians wiki page including but not limited to the page views.
The page views are then ranked in descending order with the musician with the highest page view being the first and the musician with the lowest page views being the last. A list of 5 popular Nigerian musicians based on their wikipedia page views will also be generated.
