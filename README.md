1. Introduction
This assignment will help you to consolidate the concepts learnt in the session.

2. Problem Statement

In this assignment, students will be using the K-nearest neighbors algorithm to predict
how many points NBA players scored in the 2013-2014 season.
A look at the data
Before we dive into the algorithm, let’s take a look at our data. Each row in the data
contains information on how a player performed in the 2013-2014 NBA season.
Download 'nba_2013.csv' file from this link:
https://www.dropbox.com/s/b3nv38jjo5dxcl6/nba_2013.csv?dl=0
Here are some selected columns from the data:
player - name of the player
pos - the position of the player
g - number of games the player was in
gs - number of games the player started
pts - total points the player scored
There are many more columns in the data, mostly containing information about average
player game performance over the course of the season. See this site for an explanation
of the rest of them.
We can read our dataset in and figure out which columns are present:
import pandas

with open("nba_2013.csv", 'r') as csvfile:
nba = pandas.read_csv(csvfile)

NOTE: The solution shared through Github should contain the source code used and
the screenshot of the output.

3. Output

N/A
