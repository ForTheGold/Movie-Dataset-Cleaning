# Movie_Analysis

Data cleaning of a file to be used in a hackthon involving the predictive analysis of the popularity of independent movies.  This work was done in Python, Pandas, SQL and the ELT pipeline.

This is an example showcasing my data cleaning skills.  This was a messy file that was to be used in a hackathon run by a small company similar to NetFlix.  The data was extremely messy and needed to be cleaned for the users.  This is process that I followed in order to do just that.

## Background

Amazing Prime is a video streaming service similar to NetFlix that has just launched.  The website is looking for developers who can write an algorithm to predict what movies will be popular in the future.  In order to accomplish this task, Amazing Prime is setting up a Hackathon in which they provide data for participants to analyze.  There are a few files of data that have been scraped and collected from the internet, but they are not clean.  The purpose of this project is to apply the ETL process to give clean and usable data to participants in the Hackathon.

## Problems

We used the ETL pipeline in order to transform the data into a more usable set.  There were many inconsistencies and irregularities in the data.  For instance, many of the columns were of the wrong data type, there were multiple columns providing the same information i.e. “Directed by” as well as “Director”, numerical types that were expressed as strings i.e. “4 million” as opposed to 4000000, along with many other problems.

## Process

I went through the data to find as many inconsistencies as I could and then applied transformations on the data in order to make it cleaner and easier to use.  This included changing the data types of the columns, changing some of the ways that the data was expressed as well as adding in values where the values were null.  I have also placed the final data in a database that can be readily accessed.

## Results

After having gone through the process of cleaning the data, we are now ready with the final data set that has been cleaned and uploaded into the database.

## Technologies

* Pandas
* Numpy
* SQLAlchemy
* RegEx
* psycopg2
* Python
* JSON
* ETL
* Data Cleaning
