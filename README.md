# Accenture-Social-Buzz-Analysis

Client name: Social Buzz Client industry: Social media & content creation Year established: 2010 Location of HQ: San Francisco Number of employees: 250 Client background: Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. 

**Excel Skill applied**

- Data Merging 
- Vlookup
- Pivot table

## Problem Statement

The client wants to understand the popularity of different content categories using visualization on a sample dataset.The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”

## Data Sourcing

The sample dataset was produced by the Social Buzz director from companies social media engagement dataset.

It has 3 different tables :
**1. Reaction Table**
**2. Content table**
**3. Reaction type table**

## Data Transformation/Cleaning

- I find and replaced some special characters that are in some columns
- I deleted blank space
- I renamed some columns

## Date Modelling

The data is a three table dataset and so i just merge the columns together using the VLOOKUP formula
The new table now consist of 8 columns namely; _No., ContentID, ReactionType, DateTime, ContentType, Categories, Sentiment, Score_

## Problem Statement 1

1.  The client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”

I use the pivot table to check for the categories with the highest score
The insight shows **Animal, Science, Eating healthy, Technology and food** are the Top 5 Content Categories
