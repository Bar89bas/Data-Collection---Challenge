 Data-Collection---Challenge
 
 Overview:
This project involves the full web-scraping and data analysis. Based on the id and attributes of HTML elements in Mars news site and Mars Temperature Data Site webpage, the information has been extracted via both automated browsing with Splinter and HTML parsing with Beautiful Soup. 

Scope: 
This report focuses on the extracting information from https://static.bc-edx.com/data/web/mars_news/index.html and https://static.bc-edx.com/data/web/mars_facts/temperature.html webpage and storing them in java scrip object notification and comma separated value file. Moreover, the dataframe has been created from the tabular format and further analysis has been performed. 

Methodology:
1.	Automated browsing is used to visit the Mars news site and the HTML code is extracted with Beautiful Soup python libray.
2.	The title and preview text of Mars news site were scraped and extracted and the scraped information is stored in the specified python data structure (dictionary)
3.	The HTML table is extracted into a pandas Dataframe. And statistical analysis is performed. 

Findings:
1.	How many months in exist on mars?
2.	How may Martian days’ worth of data are there?
3.	Which month, on average has the lowest\highest temperature?
4.	Which month on average has the lowest\highest atmospheric pressure?
5.	How may terrestrial days exist in a Martian year? Visual estimation. 
