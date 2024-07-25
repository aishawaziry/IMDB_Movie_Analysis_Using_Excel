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
    * Added a column representing the number of genres each movie has.
2. Profit
    * Created a column for profit, calculated as the difference between gross earnings and budget (gross - budget).
3. Rating Category
    * Added rating category based on IMDb scores.
4. Decade 
    * Added decade column to categorize the movie release years into respective decades.

## Data Analysis

### In this section, we will analyze the IMDb dataset to uncover insights and answer key questions.
### Key Questions and Insights

- - - -

1. What are the most common genres associated with the most votes?
    * Identify the genres that receive the highest number of votes from viewers.
<p align="center">
  <img src="https://github.com/user-attachments/assets/f5e112d3-0eda-4348-a4ec-a52ae8a695dd" alt="genre vs vote" width="45%">
  <img src="https://github.com/user-attachments/assets/de736fab-84cd-48cd-994e-f2b877dc10f8" alt="Picture1" width="45%">
</p>

2. What are the highest-ranking genres?
    * Determine which genres have the highest average ratings.
<p align="center">
  <img src="https://github.com/user-attachments/assets/b0edebce-6e2c-40d0-a910-b3b19be03360" alt="genre vs score" width="45%">
  <img src="https://github.com/user-attachments/assets/ab9d90b8-e14f-4885-82d6-e5872864da8e" alt="Picture2" width="45%">
</p>

3. Rating category and count: How many people give each rating?
    * Analyze the distribution of ratings and the number of people who give each rating.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a2cfbde9-b543-4426-8e40-9779c34c9b3e" alt="category" width="45%">
  <img src="https://github.com/user-attachments/assets/ec3b5567-bcc2-42c4-abf7-8496d89c2cd7" alt="Picture5" width="45%">
</p>

4. What are the top 10 movies with the highest profits?
    * List the movies that have generated the highest profits. 
<p align="center">
  <img src="https://github.com/user-attachments/assets/c83383dd-d4f4-4e8a-8717-236f4c5001f4" alt="title vs profit" width="45%">
  <img src="https://github.com/user-attachments/assets/512e1942-206d-4155-ace6-485cd1c38efb" alt="Picture3" width="45%">
</p>

5. Compare profit and budget for the top 10 movies with the highest profits.
    * Analyze the relationship between the budget and profit for the top 10 most profitable movies.
<p align="center">
  <img src="https://github.com/user-attachments/assets/0d280a05-5088-4a35-84eb-6c7cb99b9dfa" alt="title vs total" width="45%">
  <img src="https://github.com/user-attachments/assets/5988f44b-2cbf-45df-ba0f-34765e0b3647" alt="Picture4" width="45%">
</p>

6. Top 10 directors with the highest IMDb scores. 
    * Identify the directors whose movies have the highest average IMDb scores.

<p align="center">
  <img src="https://github.com/user-attachments/assets/f3faa1b7-c0a6-4791-a570-d51f130f691d" alt="director" width="45%">
  <img src="https://github.com/user-attachments/assets/922d2826-104d-485e-988d-128166d1ea73" alt="Picture6" width="45%">
</p>

7. Most common 5 languages in the dataset.
    * Determine which languages are most frequently represented in the dataset.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e227ecd4-e6e1-4617-9b6f-74aafcfd73d2" alt="language count" width="45%">
  <img src="https://github.com/user-attachments/assets/a246d00e-3e5d-4727-a194-93dd6c487e52" alt="Picture7" width="45%">
</p>

8. Top 10 highest-scoring languages.    
    * Identify the languages that have the highest average movie scores.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c788218e-f827-441e-8d12-bfa3a55fba28" alt="language score" width="45%">
  <img src="https://github.com/user-attachments/assets/ca3a9f90-e21f-4362-a116-f3254de0a563" alt="Picture8" width="45%">
</p>

9. Top 10 actors with the highest average votes.
    * Find the actors whose movies receive the highest average number of votes.
<p align="center">
  <img src="https://github.com/user-attachments/assets/336befdd-9064-4455-8b85-15c7b263ee71" alt="actor vote" width="45%">
  <img src="https://github.com/user-attachments/assets/b7a41b62-9f78-4452-a908-da00ba482c48" alt="Picture9" width="45%">
</p>

10. See the number of movies created in each decade.
    * Count of movies produced in each decade.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5af244ae-325d-455e-a0fd-78d7256a9b3e" alt="decade" width="45%">
  <img src="https://github.com/user-attachments/assets/078addbd-0886-4b6b-aaf1-341c81edee70" alt="Picture10" width="45%">
</p>


## Dashboard Analysis
#### This dashboard presents a comprehensive visual analysis of the IMDb dataset, allowing for interactive exploration of key insights.

<p align="center">
    <img src="https://github.com/user-attachments/assets/ba20bd62-388c-48f6-be5e-62acca968494https://github.com/user-attachments/assets/ba20bd62-388c-48f6-be5e-62acca968494">
</p>

## Conclusion 
#### This project aims to analyze the provided dataset, revealing several meaningful insights that would have been challenging to uncover through manual exploration. By using data analysis and visualization tools, we can efficiently extract and understand critical patterns and trends within the IMDb dataset.