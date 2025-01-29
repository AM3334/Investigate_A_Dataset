# Investigate_A_Dataset

## Project: Investigate a Dataset - [TMDB 5000 Movie Dataset]

### Table of Contents
- Introduction  
- Data Wrangling  
- Exploratory Data Analysis  
- Conclusions  

## Introduction  

### Dataset Description  
What can we say about the success of a movie before it is released? Are there certain companies (Pixar?) that have found a consistent formula? Given that major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?  

This is a great place to start digging into those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.  

This dataset contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. Certain columns, like ‘genres’ and ‘production_companies’, contain multiple values separated by pipe (|) characters.  

## Questions for Analysis  
1. Which companies produced the most movies in the dataset?  
2. How much effect do production companies have on the flop or success of a movie, estimating success by revenues and budgets?  
3. Is revenue and budget correlated? What's the relationship between them?  

## Data Wrangling  
- Loaded and merged datasets.  
- Handled missing data and optimized data types.  

## Exploratory Data Analysis  
- Investigated relationships between budget and revenue.  
- Investigated how big a production company is based on the number of movies it produces.  
- Analyzed the impact of production companies on the flop or success of a movie.  

## Conclusions  
1. The leading company in movie production based on occurrences is **Warner Bros**.  
2. The success or failure of a movie may depend on the brand name of the company and its advertising capabilities.  
3. The relationship between budgets and revenues is **strong and positive**.  

## Limitations  
- **Missing Critical Data** – The dataset lacks key information like release season and competing releases, which can significantly impact a movie’s success and distort the budget-revenue relationship.  
- **Time-Based Popularity Trends** – The analysis does not account for how some movies gain popularity over time, making a time-series evaluation crucial for understanding long-term success patterns.  

## Further Analysis  
- The most popular genres in the industry.  
- Traits linked to high-revenue movies.  
- Characteristics of films that gain popularity over time.  
