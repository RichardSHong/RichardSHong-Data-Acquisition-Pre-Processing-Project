Google News Data set
DSCI 511 Group Project
Jenni Bochenek, Ian Fitzsimmons, Richard Hong, Katherine Houseman
December 11, 2018

----------------------------------------------------------------------
README CONTENTS

Introduction
Installation
Code and Data Structures


Introduction
This tool extracts content from Google News categories (Headlines, US, World, Business, Nation, Health, Sports, Tech, and Entertainment) and is configured to scrape on an hourly basis. The code is written in Python 3. 

Installation
The following modules are needed in order to run this code:

feedparser
newspaper
nltk


Code and Data Structures (Katherine’s note - this part not yet finished!)
The code is designed to create separate files each time it runs:

grss.json
This file contains the eight specified Google News categories and their accompanying RSS url.

articles.json
This file contains the news article

keywords_by_type.json
This file contains keywords 

keywords.json
This file contains… 

headlines.json
This file contains… 

In order to maintain a continuous data acquisition stream, a script in the Chrontab is used to collect data hourly. 










