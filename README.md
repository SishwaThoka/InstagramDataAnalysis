# InstagramDataAnalysis
DBMS Final Project

Instagram has shown exponential growth as an innovative social media platform, attracting a large number of followers.

Influencers are able to leverage Instagram's various features and products to significantly increase their followers, leading to new avenues of growth.

The purpose of this database is to collect and maintain data on influencers, comments, posts, reels, users, followers, and likes to draw inferences on effective ways to connect with audiences.

The database aims to provide insights that can help businesses and individuals enhance their Instagram presence and engage with their target audience more effectively.

Developed views to track important metrics such as follower growth rate, engagement rate, and identification of popular influencers, providing actionable insights for strategic decision-making. 

Utilized Power BI to create visually engaging reports showcasing top Instagram users by follower count and sentiment analysis of user comments. 


# Functions/ Triggers/ Stored Procedure:

Created Function to implement a table level check constraint to refrain the user from adding negative comments if the limit exceeds 7

Created Function and Triggers to Calculate the Likes Count. Similarly, we have created functions and triggers for Comments Count, Interactions Count (Likes + Comments)

Created triggers to update the Followers count in Users Table and to update duration in the UserLogin Table

Created a trigger to insert post, stories, reels based on media type. Similarly, created a trigger to insert likes and comments in the respective tables using interaction type

Created Stored Procedure to get Top five Influencers

