<!-- # Netflix Movies Duration Analysis
Explore trends in movie duration using Netflix data through exploratory data analysis (EDA). Investigate factors contributing to the decline in movie length over time. -->

# Netflix Movie Duration Analysis

In this exploratory data analysis, we investigate the hypothesis that movies are getting shorter over time using a dataset from Netflix. We follow a systematic approach to filter the data, analyze movie durations, and visualize the trends.

## Data Loading and Preparation

We begin by loading the provided CSV file `netflix_data.csv` and storing it as `netflix_df`. We then filter the data to remove TV shows, creating a subset called `netflix_subset`. Further, we focus on movie data, retaining relevant columns such as title, country, genre, release year, and duration, saving this as `netflix_movies`.

## Investigating Movie Durations

Next, we filter `netflix_movies` to find movies shorter than 60 minutes, which we save as `short_movies`. This subset allows us to inspect possible contributing factors to shorter movie durations.

## Analyzing Trends Over Time

To visualize trends in movie durations over the years, we use a scatter plot. We iterate through the rows of `netflix_movies`, categorizing movies into genre groups ("Children", "Documentaries", "Stand-Up", and "Other") and assign colors accordingly. We then create a scatter plot of movie duration by release year, labeling the axes appropriately and titling the plot as "Movie Duration by Year of Release".

## Conclusion

Upon inspecting the plot and analyzing the data, we address the question: "Are we certain that movies are getting shorter?" Based on our analysis, the answer is either "yes" or "no", depending on the observed trends in movie durations over the years.


