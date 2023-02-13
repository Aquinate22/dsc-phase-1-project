# Phase 1 Project

# Introduction
Data Analysis of movies for Microsoft Company

# Business Problem
Looking into movie genres
![image](https://user-images.githubusercontent.com/121969694/218340139-daa607cf-7dc6-4da5-a4d3-2fb6842179a5.png)


## Project Overview

using exploratory data analysis to generate insights for a business stakeholder.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.
### Business Understanding
The business problem was broken down to three questions:
* What genres are currently doing the best at box office?
* How much is needed to produce a worldclass movie?
* What effect does movie title have on the popularity?
### The Data
* tmdb.movies
* imdb.title.basics
* tn.movie_budgets


### Data mining and Data cleaning
Collected the data necessary to perform the analysis and read the data in csv format.
The data had to have movie title to answer the third question, it had to have production budget to answer the second question and lastly it had to be grouped into the most popular genres.
During data cleaning process:
* missing values,
* duplicates,
* some unnecessary columns,
* and outdated  were dropped
We were left with up-to-date data(release year>2011) with no missing and duplicated rows.
Some columns were also renamed
### Data exploration;
The mean and median value of the budget df was obtained
Various plots were plotted to show the relationship between different variables of the data.

