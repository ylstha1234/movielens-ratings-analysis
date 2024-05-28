# Finding the Ratings of Movie with Movie-lens Datasets 
# Project Overview
This project aims to analyze movie ratings using the MovieLens dataset. The analysis includes listing movies and users along with the counts of ratings, identifying Movie IDs and Users with at least one rating, and providing maximum, minimum, and average ratings for both users and movies. The implementation uses PySpark DataFrame APIs and SQL queries.
# Project Description
The MovieLens dataset is a rich source of information for understanding user preferences and movie ratings. This project leverages this dataset to gain insights into movie ratings, user behaviors, and preferences. By performing exploratory data analysis and applying PySpark DataFrame APIs, we can extract meaningful patterns and statistics that are valuable for various applications, such as developing recommendation systems and marketing strategies.
MovieLens data sets were collected by the GroupLens Research Project at the University of Minnesota. This data set consists of: * 100,000 ratings (1-5) from 943 users on 1682 movies. * Each user has rated at least 20 movies. * Simple demographic info for the users (age, gender, occupation, zip). The data was collected through the MovieLens web site (movielens.umn.edu) during the seven-month period from September 19th, 1997, through April 22nd, 1998. This data has been cleaned up - users who had less than 20 ratings or did not have complete demographic information were removed from this data set. Neither the University of Minnesota nor any of the researchers involved can guarantee the correctness of the data, its suitability for any particular purpose, or the validity of results based on the use of the data set. The data set may be used for any research purposes under the following conditions: 
1.	The user may not state or imply any endorsement from the University of Minnesota or the GroupLens Research Group.
2.	The user must acknowledge the use of the data set in publications resulting from the use of the data set (see below for citation information).
3.	The user may not redistribute the data without separate permission.
4.	The user may not use this information for any commercial or revenue-bearing purposes without first obtaining permission from a faculty member of the GroupLens Research Project at the University of Minnesota.
If you have any further questions or comments, please contact GroupLens grouplens-info@cs.umn.edu.

# Description of Data Files 
1.	ml-data.tar.gz - The compressed tar file that contains u.data, u.item, u.user, and others.
2.	u.data - The full u data set, 100000 ratings by 943 users on 1682 items. Each user has rated at least 20 movies. 
3.	u.info - The number of users, items, and ratings in the u data set.
4.	u.item - It has an information about the items (movies).
5.	u.genre - A list of the genres.
6.	u.user - Demographic information about the users; this is a tab separated list of user id | age | gender | occupation | zip code.
7.	u.occupation -- A list of the occupations. 
Besides, there are other files in the zip file folder.

# Use Cases
1.	List all movies along with the number of ratings.
2.	Display users and the count of ratings they've given for movies.
3.	Identify Movie IDs with at least one user rating.
4.	List users who have rated at least one movie.
5.	Provide lists of users and movies with their maximum, minimum, and average ratings. 
# Milestone Name
1.	Data Ingestion and Preparation
2.	Exploratory Data Analysis with SQL
3.	User Ratings Analysis
4.	PySpark DataFrame API Implementation
# Final Output
The final output of this project includes several key insights and data visualizations derived from the MovieLens dataset:
1.	Most rated movies: A list of movies sorted by the number of ratings received. 
2.	Highest rated movies: A list of movies with the highest average ratings.
3.	User rating counts: A summary of the number of ratings provided by each user.
4.	Movie rating statistics: Average, minimum, and maximum ratings for each movie.
5.	User rating statistics: Average, minimum, and maximum ratings for each user.
# Review
The MovieLens Movie Ratings Analysis project successfully demonstrates how large datasets can be leveraged to extract meaningful insights into user preferences and behaviors. By utilizing PySpark and SQL for data processing and analysis, the project efficiently handles large-scale data and provides comprehensive results that are applicable to real-world scenarios, such as enhancing user experience through personalized recommendations and informed decision-making for content production and marketing strategies.
# Citation
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. DOI=http://dx.doi.org/10.1145/2827872  

