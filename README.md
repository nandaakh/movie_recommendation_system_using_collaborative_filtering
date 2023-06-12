# movie_recommendation_system_using_collaborative_filtering

**Background**

Movie recommendation systems have become very important in the entertainment industry to help users find films that suit their preferences. In this project, we aim to develop a film recommendation system using the Collaborative Filtering method. Collaborative Filtering is a technique that focuses on comparing user preferences to present relevant recommendations. By using this approach, we hope to provide users with personalized and accurate movie recommendations.

**Objective**

The main goal of this project is to build a movie recommendation system that can provide relevant recommendations based on user preferences. We want to provide users with a better experience in finding films that are interesting and according to their tastes. In addition, this project also aims to increase understanding of the Collaborative Filtering method and its application in the film recommendation domain.

**Data Used**

For this project, we are using two data tables namely "movies" and "ratings". The "movies" table contains information about available films, including movie ID, title, and related genres. Meanwhile, the "ratings" table contains information about the rating given by the user for each film, including the user ID, movie ID, rating, and timestamp. This data provides insight into user preferences for existing films.

**Process Performed:**

1. Data Preprocessing: Data from the "movies" and "ratings" tables are read using the pandas library. Performed handling of missing or invalid values in the data. If necessary, data transformation or encoding is performed, for example changing genres into binary features with one-hot encoding.
2. Data Analysis: Data exploration is carried out to understand the characteristics of the dataset. Identify descriptive statistics and visualize data, such as the distribution of film ratings or the distribution of film genres. It also identifies trends or patterns in the data, such as the most popular genres or films with the highest ratings.
3. Application of the Collaborative Filtering Model: The data is separated into training data and test data. Created a user-item matrix based on rating data. The appropriate Collaborative Filtering algorithm is selected, for example User-based Collaborative Filtering or Item-based Collaborative Filtering. The Collaborative Filtering model is trained using training data, and rating predictions are made for users and films that are not in the training data.
4. Model Evaluation: Test data is used to evaluate model performance. A comparison is made between the predicted results and the actual value using evaluation metrics, such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Precision, Recall, and F1-Score. Evaluation results are used to analyze model performance and look for potential to improve it.
5. Visualization of Results: Visualize the distribution of predicted results and compare them with the actual values. For example, visualizing the distribution of rating prediction results to see how far the model can accurately predict ratings within a certain range.

By running this project in Jupyter Notebook or Google Colab, you will be able to see interactively the steps involved in building a movie recommendation system using Collaborative Filtering. You can also do further exploration of the data and make adjustments or improvements to the model used.
