# Introduction

Web scraping is a technique using which the webpages from the internet are fetched and parsed to understand and extract specific information similar to a human being. Web scrapping consists of two parts:
 Web Crawling
 Accessing the webpages over the internet and pulling data from them. 
 HTML Parsing
 Parsing the HTML content of the webpages obtained through web crawling and then extracting specific information from it. 
Hence, web scrappers are applications/bots, which automatically send requests to websites and then extract the desired information from the website output. 
Let’s take an example:  
how do we search for images online?
 We go to a website that shows images, and then we enter the keyword to search for the photos. 
 The website shows us the images.
 We decide to download the image(s). 
What if there is a computer program that can do all of these for us? That’s what web scrappers necessarily do. They try to understand the webpage content as a human would do. 
Let’s take an example where we need thousands of images to train our object detection/classification model. It is an excellent use case for implementing an image scraper. 

# Prerequisites: 
The things needed before we start building a python based web scraper are:
 Python installed.
 A Python IDE (Integrated Development Environment): like PyCharm, Spyder, or any other IDE of choice (Explained Later) 
 Flask Installed. (A simple command: pip install flask)
 MongoDB installed (Explained Later).
 Basic understanding of Python and HTML.
 Basic understanding of Git (download Git CLI from https://gitforwindows.org/ ) 
