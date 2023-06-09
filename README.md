# Movie_Recommendation_System

## INTRODUCTION TO THE DATASET

We chose movie data set for data analysis. This data set contains information about 1000 movies having the highest ratings collected from IMDb (Internet Movie Database), including user ratings, revenue, genre, timeline and year of release. We would like to find some interesting patterns in the dataset.

## INTRODUCTION TO THE PROBLEM

The dataset may contain null values, special characters and objects in an int type column. Talking about our data specifically, it contains null values as well as special characters. ‘year’, ‘votes’, and ‘gross’ are factors or their datatype is object i.e. they contain alphabets or special characters. 

## AIM:
- **Aim-1:** To make a recommendation system which suggests movies of the genre we input and print them in descending order on the basis of their ratings.
* **Aim-2:** To input a movie name and display its timeline, year of release, genre and IMDB rating.
+ **Aim-3:** To input a year/ time period and to display movies released during that period.

The primary goal of the project is to go through the dataset and the general data analysis process using numpy, pandas, matplotlib and sns. This contains four parts:
1. Introduction
2. Data Cleaning/Preprocessing
3. Exploratory data analysis
4. Conclusions

![Proposed Workflow](https://www.linkpicture.com/q/Workflow.png)

## RESULT :
With the completion of this mini project we have learnt how to deal with dataset (csv file). To summarize, first we import the vital Python libraries, we read the csv file, we clean the data and we explore the data (using graphs as well). This project helped us analyse the data and create visualizations that helped us answer a few curiosities that we had about movie dataset.

Following are the conclusions we have derived after thoroughly exploring the data :

* After cleaning the data and setting the index we had 747 rows and 9 columns.
+ There are no outliers in the dataset.
- The shortest runtime in the entire dataset is 66 minutes and the longest runtime in the entire dataset is 238 minutes.
* The average number of votes garnered by 70% of the movies from the dataset is 428718.39999999985.
+ The lowest metascore in the entire dataset is 28.0 which is received by the movie 'I Am Sam'
- 'The Shawshank Redemption' has the highest number of votes i.e. 2400,000
* 'Star Wars: Episode VII - The Force Awakens' has the highest Box Office collection ($ 700M +).
+ 130+ movies received 7.7 rating according to IMDb.
- "Avengers: Endgame, Ford v Ferrari, Portrait of a Lady on Fire, Toy Story 4, The Irishman, 1917, Little Women, Knives Out, Parasite, Once Upon a Time... In Hollywood, Jojo Rabbit, Joker, The Peanut Butter Falcon, Gully Boy and Marriage Story" are the movies released in 2019 according to the IMDb dataset.
