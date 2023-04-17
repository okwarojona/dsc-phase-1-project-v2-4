### Final Project: Movie Data Analysis


.This is the final project submission for the movie data analysis project conducted by Okwaro Jonathan Aggrey. The project aims to analyze various aspects of movie data, including genre distribution, release dates of successful movies, audience ratings, and budget and revenue analysis.

### Objectives
The main objectives of this project are:

. Analyze the genre distribution: Count the frequency of each genre in the dataset and visualize the genre distribution using a bar chart.
. Analyze the release dates of successful movies: Identify any patterns or trends in the release dates of successful movies and visualize them using line charts or histograms.
. Analyze audience ratings: Clean and analyze the audience rating data, including converting ratings to numeric values, and visualize the distribution of ratings using histograms or box plots.
. Budget and revenue analysis: Clean and analyze the budget and revenue data, including removing unnecessary characters and converting to numeric values, and visualize the relationships between budget, revenue, and other variables using scatter plots or regression analysis.

### Data Cleaning
The project starts with data cleaning to ensure the integrity and accuracy of the analysis. The following steps are performed for data cleaning:

. Budgets data: Read the budgets data from a CSV file and convert the release date to a datetime format. Remove unnecessary characters and convert the budget and revenue columns to numeric values. Remove rows with placeholder values of 0 and drop any missing values or duplicate rows.
. Reviews data: Read the reviews data from a TSV file and drop rows with missing values in review, rating, critic, and publisher columns.   Convert the rating values to numeric and drop any remaining missing values.
. Movies information data: Read the movies information data from a TSV file and drop unnecessary columns including currency, studio, box office, and rating. Fill missing values in the synopsis column with an empty string, drop rows with missing values in genre, theater date, and DVD date columns. Fill missing values in director and writer columns with 'Unknown'. Remove unnecessary characters from the runtime column and convert it to numeric. Drop rows with missing values in the runtime column.

### Data Merge
After cleaning the datasets, they are merged based on the 'id' column to create a combined dataset for further analysis. The merged dataset includes information from the movies information, budgets, and reviews datasets.

### Statistical Analysis
The statistical analysis includes various visualizations and exploratory data analysis to gain insights into the movie data. The following analyses are performed:

. Genre Distribution: Count the frequency of each genre in the merged dataset and visualize the genre distribution using a bar chart.
   
.Release Dates Analysis: Analyze the release dates of successful movies to identify any patterns or trends. Visualize the analysis results using line charts or histograms.
  
.Audience Ratings Analysis: Analyze the audience ratings data, including distribution and trends. Visualize the analysis results using histograms or box plots.

.Budget and Revenue Analysis: Analyze the budget and revenue data, including relationships between budget, revenue, and other variables. Visualize the analysis results using scatter plots or regression analysis.

### Conclusion
The movie data analysis project provides insights into various aspects of movies, including genre distribution, release dates, audience ratings, and budget and revenue analysis. The analysis results are presented in visualizations and provide valuable information for further analysis or decision-making in the movie industry.



### Project Files
The project includes the following files:
. movie_data_analysis.ipynb: Jupyter notebook containing the code for data cleaning, data merge, and statistical analysis.
.tn.movie_budgets.csv.gz: CSV file containing the budgets data.
.rt.reviews.tsv.gz: TSV file containing the reviews data.
.rt.movie_info.tsv.gz: TSVic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!
