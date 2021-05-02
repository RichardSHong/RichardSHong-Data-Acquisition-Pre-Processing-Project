Google News Data set

DSCI 511 Group Project

Jenni Bochenek, Ian Fitzsimmons, Richard Hong, Katherine Houseman

December 11, 2018

----------------------------------------------------------------------

## README CONTENTS

- Introduction
- Installation
- Code and Data Structures


### Introduction

This tool extracts content from Google News categories (Headlines, US, World, Business, Nation, Health, Sports, Tech, and Entertainment) and is configured to scrape on an hourly basis. The code is written in Python 3.

### Installation

The following modules are needed in order to run this code:

feedparser

newspaper

nltk


### Data Structures

We have 4 main outputs from this code:

1. A dictionary of scraped news articles
2. A list of the headlines of all news articles in dictionary
3. A file of word counts per day
4. A file of word counts nested within RSS feed per day

In total, we have 16 files for a total of 164 MB of data:

1. articles.json (151 MB)
2. headlines.txt (1.97 MB)

3 and 4. (between 1-300 KB)

8DEC\_daily\_\_Keywords\_By\_Type\_Info.json

8DEC\_daily\_\_Keywords\_Info.json

8DEC\_hourly\_keywords.json

8DEC\_hourly\_keywords\_by\_type.json

9DEC\_daily\_\_Keywords\_By\_Type\_Info.json

9DEC\_daily\_\_Keywords\_Info.json

9DEC\_hourly\_keywords.json

9DEC\_hourly\_keywords\_by\_type.json

10DEC\_daily\_\_Keywords\_By\_Type\_Info.json

10DEC\_daily\_\_Keywords\_Info.json

10DEC\_hourly\_keywords.json

10DEC\_hourly\_keywords\_by\_type.json

11DEC\_hourly\_keywords.json

11DEC\_hourly\_keywords\_by\_type.json


#### In order to maintain a continuous data acquisition stream, a script in the Chrontab is used to collect data hourly.
