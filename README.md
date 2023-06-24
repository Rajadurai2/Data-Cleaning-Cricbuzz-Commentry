# Data Extraction from the commentry text 

In this repository I write a python script to Extract the data from the Commentry text scraped from the cricbuzz site

### Prerequisites

The things you need before installing the software.

* You need Python
* And you need Pandas,re (modules)

### Installation

A step by step guide that will tell you how to get the development environment up and running.

```
$ git clone 'https://github.com/Rajadurai2/Data-Cleaning-Cricbuzz-Commentry.git'
$ cd Cricbuzz-Webscrapping
$ python data_cleaning.ipynb
```

## About my code

From this script we can 

```
- Before this you can see the Web_Scrapping repo to what the dataset contains 'https://github.com/Rajadurai2/Cricbuzz-Webscrapping'
- That dataset contains only commentry text and toss text and winners text
- We can Extract the Commentry_text to get some useful data like runs,ball_length_ball_line,ball_destination etc....
- I wrote separate functions to do that 
- So you can extract the data by excecuting the each functions
```

## result.csv  

------> After excecuting this file we can extract the following data from the commentry_text and Toss text
```
1.Toss_winner
2.Toss_decesion(toss_choosen)
3.batting_team
4.Bowling_team
5.batsman
6.bowler
7.Runs
8.extra
9.ball_length
10.ball_line
11.ball_destination
12.Shot_name
13.out_type
14.ball_spped
```

