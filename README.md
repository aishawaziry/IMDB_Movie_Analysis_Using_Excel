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
4. Decade 
    * Added decade column to categorize the movie release years into respective decades

## Data Analysis

### In this section, we will analyze the IMDb dataset to uncover insights and answer key questions.
### Key Questions and Insights

- - - -

1. What are the most common genres associated with the most votes?
    * Identify the genres that receive the highest number of votes from viewers.
<p align="center">
  <img src="https://github.com/user-attachments/assets/a4d6292c-8847-4263-beb1-2415f21ae60c" alt="genre vs vote" width="45%">
  <img src="https://github.com/user-attachments/assets/82b9cc98-078a-492a-b658-3aa9ca45c7cf" alt="Picture1" width="45%">
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
  <img src="https://github.com/user-attachments/assets/feee7b02-4829-4941-92b8-2f547649741e" alt="category" width="45%">
  <img src="https://github.com/user-attachments/assets/7220d06a-bcc8-4d92-bb04-c37f53b732c7" alt="Picture5" width="45%">
</p>

4. What are the top 10 movies with the highest profits?
    * List the movies that have generated the highest profits. 
<p align="center">
  <img src="https://github.com/user-attachments/assets/ba23c903-ea38-4005-a437-97b0f6f5bf09" alt="title vs profit" width="45%">
  <img src="https://github.com/user-attachments/assets/512e1942-206d-4155-ace6-485cd1c38efb" alt="Picture3" width="45%">
</p>

5. Compare profit and budget for the top 10 movies with the highest profits.
    * Analyze the relationship between the budget and profit for the top 10 most profitable movies.
<p align="center">
  <img src="https://github.com/user-attachments/assets/f87147fe-d7c2-47d6-8f0f-230a3cc655f2" alt="title vs total" width="45%">
  <img src="https://github.com/user-attachments/assets/fa6caa4c-9473-4cba-b671-ffc7118e529c" alt="Picture4" width="45%">
</p>

6. Top 10 directors with the highest IMDb scores. 
    * Identify the directors whose movies have the highest average IMDb scores.

<p align="center">
  <img src="https://github.com/user-attachments/assets/227b0cdf-ad4f-4b15-9759-3cb21be94209" alt="director" width="45%">
  <img src="https://github.com/user-attachments/assets/ee4547ec-0091-4efe-927c-f9f7c2c345d7" alt="Picture6" width="45%">
</p>

7. Most common 5 languages in the dataset.
    * Determine which languages are most frequently represented in the dataset.

<p align="center">
  <img src="https://github.com/user-attachments/assets/49c1437d-eacb-4a65-9332-510315057dde" alt="language count" width="45%">
  <img src="https://github.com/user-attachments/assets/6b5fc0dd-d44a-4e12-beb4-3d5b27f50f55" alt="Picture7" width="45%">
</p>

8. Top 10 highest-scoring languages.    
    * Identify the languages that have the highest average movie scores.

<p align="center">
  <img src="https://github.com/user-attachments/assets/564dc15d-dbf0-4e39-9b74-eaf6e7fbca4e" alt="language score" width="45%">
  <img src="https://github.com/user-attachments/assets/fe0174fa-83ef-436d-af94-3d004d830827" alt="Picture8" width="45%">
</p>

9. Top 10 actors with the highest average votes.
    * Find the actors whose movies receive the highest average number of votes.
<p align="center">
  <img src="https://github.com/user-attachments/assets/19436a7e-d5b6-4120-9d47-cfbd756e607c" alt="actor vote" width="45%">
  <img src="https://github.com/user-attachments/assets/2e8c3586-4e06-41a1-8343-a8ada59859e0" alt="Picture9" width="45%">
</p>

10. See the number of movies created in each decade.
    * Count of movies produced in each decade.

<p align="center">
  <img src="https://github.com/user-attachments/assets/de60bc4e-6127-4c85-b089-6f4810c6dfc1" alt="decade" width="45%">
  <img src="https://github.com/user-attachments/assets/64a31341-5098-48c9-bcb2-c8372e3104d7" alt="Picture10" width="45%">
</p>