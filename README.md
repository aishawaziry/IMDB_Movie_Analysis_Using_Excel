# IMDB Movie Analysis Using Excel
<p align="center">
    <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*f-bF79_zFHGXEhJvx2WPLg.jpeg"> 

## Project Description
#### IMDb is a globally recognized platform that provides ratings and reviews for movies, contributed by both users and critics. It also offers detailed profiles of directors, actors, and financial information about movies.This project aims to perform a comprehensive analysis of a provided IMDb dataset using Microsoft Excel.
 
#### Excel is powerful data analysis and visualization tools, we will clean the dataset, perform statistical analysis, and answer key questions to gain deeper insights into movie ratings, financial performance, and other critical factors. 

## Dataset Overview
#### The dataset contains 3,587 rows and the following columns:

* director_name
* num_critic_for_reviews
* gross
* genres
* actor_1_name
* movie_title
* num_voted_users
* plot_keywords
* num_user_for_reviews
* language 
* country 
* budget
* title_year
* imbd_score

## Data Cleaning
#### This step involves preprocessing the data to make it suitable for analysis.The Data Preprocessing Steps:
1. Remove Null Plot Keywords:
    * Removed rows where plot keywords are null, reducing the total from 3,587 to 3,557.
2. Handle Null In Language:
    * Found three rows with null language values.
    * Searched IMDb and filled in the missing language information.
3. Correct Actor and Director Names:
    * Fixed issues in actor and director names where characters like «, Ã, and ã appeared instead of ë.
4. Clean Movie Titles:
    * Removed the extraneous character "Ã" that was added at the end of most movie titles, ensuring they match the original movie names.

## Derived Columns
1. Number of Genres
    * Added a column representing the number of genres each movie has
2. Profit
    * Created a column for profit, calculated as the difference between gross earnings and budget (gross - budget)
3. Rating Category
    * Added rating category based on IMDb scores

## Data Analysis

### In this section, we will analyze the IMDb dataset to uncover insights and answer key questions.
### Key Questions and Insights

- - - -

1. What are the most common genres associated with the most votes?
    * Identify the genres that receive the highest number of votes from viewers.
<p align="center">
  <img src="https://github.com/user-attachments/assets/f57beaf8-5063-405b-9509-6b9d25bb048e" alt="genre vs vote" width="45%">
  <img src="https://github.com/user-attachments/assets/627d6a5f-802a-485a-bd39-b700376436b4" alt="Picture1" width="45%">
</p>

2. What are the highest-ranking genres?
    * Determine which genres have the highest average ratings.
<p align="center">
  <img src="https://github.com/user-attachments/assets/e8e977cd-5278-4289-abfb-0ea41d8e3615" alt="genre vs score" width="45%">
  <img src="https://github.com/user-attachments/assets/41c59227-45aa-461e-9499-968cf7c8d2d5" alt="Picture2" width="45%">
</p>

3. Rating category and count: How many people give each rating?
    * Analyze the distribution of ratings and the number of people who give each rating.
<p align="center">
  <img src="https://github.com/user-attachments/assets/f87147fe-d7c2-47d6-8f0f-230a3cc655f2" alt="title vs total" width="45%">
  <img src="https://github.com/user-attachments/assets/fa6caa4c-9473-4cba-b671-ffc7118e529c" alt="Picture4" width="45%">
</p>

4. What are the top 10 movies with the highest profits?
    * List the movies that have generated the highest profits. 
<p align="center">
  <img src="https://github.com/user-attachments/assets/ba23c903-ea38-4005-a437-97b0f6f5bf09" alt="title vs profit" width="45%">
  <img src="https://github.com/user-attachments/assets/512e1942-206d-4155-ace6-485cd1c38efb" alt="Picture3" width="45%">
</p>

5. Compare profit and budget for the top 10 movies with the highest profits.
    * Analyze the relationship between the budget and profit for the top 10 most profitable movies.
6. Top 10 directors with the highest IMDb scores. 
    * Identify the directors whose movies have the highest average IMDb scores.
7. Most common 10 languages in the dataset.
    * Determine which languages are most frequently represented in the dataset.
8. Top 10 highest-scoring languages.    
    * Identify the languages that have the highest average movie scores.
9. Top 10 actors with the highest average votes.
    * Find the actors whose movies receive the highest average number of votes.
