# FordGo Bikeshare Data Exploration
## by Onome David Omoghene


## Dataset

This is a dataset from a bike share company base in San Francisco, California. The dataset contains information about ride duration, client gender and age, start and end station details, client type (customer or subscriber) and bike id.
The dataset was dirty and untidy in it's raw form, so we had to perform a few wrangling operations before we could use it. This included changing datatypes, dropping rows with null values, and correcting a typo.


## Summary of Findings

This was an interesting dataset to explore, with a few oddities. We saw the gender distribution between riders; we saw that subscribers made up a majority of the rides; women rode longer, on average, than men, and that the station with the most rides wasn't the one with the longest rides. We saw some seniors riding just as long as 30-year-olds, and that a considerable number of rides were begun (and ended) around midnight, men took more rides than women, and average ride time was 11.5 minutes.
Men in their 30's make up a majority of the population, San Francisco Ferry Building has the highest average ride duration and Market St at 10th St was the favorite ride origin.

We did have to cut out a sizeable chink of the dataset that had missing information, and change the dtypes for many of the columns, and to get the top stations, we had to select only ten so that they were plotable. These may be limitations in the data for which we need more research.


## Key Insights for Presentation

As stated in the exploration, my main interest is the difference between client types, and how that correlates with number of rides taken. That will be the main presentation. We'll see the age and gender distributions.