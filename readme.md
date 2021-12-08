# Project Structure
## 1_steam_data_processing
This notebook contains all the cleaning, analysis, and feature engineering that was done on the steam dataset, including the visualizations
## 1_weighted_score
This notebook contains all the cleaning, processing, analysis, and feature engineering of the reviews dataset. This also includes the calculation of the weighted review scores for the reviews.
## 2_clustering_sol
This notebook contains the implementation of the kmeans and HAC clustering algorithms 
## 2_count_vectorization_sol
This notebook contains the implementation of the content-based filtering method, as well as some word cloud visualizations, and the hybrid solution which uses the weighted review scores to create a hybrid score.

### Data
The data used in this project are from:
https://www.kaggle.com/nikdavis/steam-store-games and https://www.kaggle.com/andrewmvd/steam-reviews
After downloading the data, move them into the Datasets folder and rename the steam_data.csv to steam.csv and the reviews to reviews.csv

### Libraries
The libraries used in this project are: numpy, pandas, seaborn, matplotlib, sklearn, wordcloud, kneed (for finding the elbow for kmeans clustering) and scipy. Those libraries will need to be imported if the notebooks are to be run
