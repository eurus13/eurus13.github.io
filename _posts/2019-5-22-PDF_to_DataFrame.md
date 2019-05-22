---
layout: post
title: PDF to Data Frame
---
This morning I was working with a crime data set that is available in pdf form- essentially data flagellation. 

Using copy and paste to convert the data from pdf to csv is manageable for about one or two pages if you value your time.
Clicking through several years worth of reports does not appeal to me, and most likely it doesn't appeal to you either.

There are two tools I came across that help automate. I chose to use Tabula only because I came across it first, but will also be trying 
out Camelot.

[Tabula](https://github.com/chezou/tabula-py)
uses raster and vectors to extract info. Pretty simple to use, but data still required a good deal of shaping and cleanup.

I did appreciate that Tabula has an argument to do pdfs batches. 

I also had an issue where I had to go back and strip all the commas out of the numerical strings and then convert them to integers ..
but that's a small price to pay. 

[Camelot](https://pypi.org/project/camelot-py/)
uses hough transform to extract tabular data and seems like it may be a more powerful tool. 

(No notes on Camelot since I haven't used it yet)
