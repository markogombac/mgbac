# mgbac
Personal files and projects

Intro 

This file was for a short group project with 4 other classmates for my class in Empirical Industrial Organization and Market Design.
It will be used in a later project to run microeconometric structural functions in order to estimate demand in 
the google play demand space.

Contents 

The file is a python web-scraping script. It uses several packages including:
- selenium (chrome webdriver package that opens a chrome instance for scrapping)
- beautifulSoup 
- numpy 
- pandas
- play-scraper (extracts a dictionary of relevant statistics based on HREF links)
- matplob for visualization 

It obtains the 500 top paid apps on the google playstore in the US and stores relevant stats on price, downloads (approximated),
ratings, developers etc. into a pandas data frame. It also categorizes these apps using categories we constructed from those provided
by the play-store to have more workable app-groups for our visualization. 

We draw summary statistics and plotted apps, coloured by category, on price and downloads. We fed this into a final report where 
we drew some insights on the data and the plots, mainly that games result in the highest download variance, and that price variance
(to a much lower degree) comes from (mainly) specialized multimedia editing apps and utility apps as these are larger files with specialized 
features and hence represnet full programs and tools more than simple apps. 


Group: 
Devyani Chugh, Paolo Bolzan, Annalia Pasqualato, Simone Cusumano, Marko Gombac(me) 
