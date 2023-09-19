# Accenture Innovation Challenge

Repository Overview:

The repository contains Machine Learning (ML) code developed for the Accenture Innovation Challenge on Product Recommendation.

Code Explanations:

Inside the repository, there are Jupyter Notebook (.ipynb) files that provide detailed code-level explanations of the ML concepts and techniques used in the solution.

Presentation Folder:

Within the repository, there is a "Presentation" folder that includes a prototype demonstration video and a PowerPoint presentation for showcasing the product recommendation solution.

UserRecommendationbyMovies:

This code segment uses Pearson similarity to measure the similarity between different users based on their movie ratings in categories like Barbie, Disney, Marvel, DC, and Transformers.
It employs a User-Based Collaborative Filtering technique for merchandise product recommendations, considering movie ratings of similar users.

UserRecommendationbyAppUsage:

This code section utilizes cosine similarity to find relevant products for different users based on their mobile app usage.
It implements an Item-Based Collaborative Filtering technique for product recommendations, focusing on mobile app categories like Gaming, JobSearch, Social, Shopping, and Entertainment.
The code has five predefined categories, but it can be expanded by collecting more products and user app usage data for a more comprehensive recommendation system.

UserRecommendationbyLocation:

In this code, the system takes a user's location, identifies similar users in the same location, and recommends products relevant to that specific area.
It combines a User-Based Collaborative Filtering approach with Content-Based Filtering techniques.

UserRecommendationbyImages:

This segment of the code allows users to input images, extracts features from those images, calculates cosine similarity between the uploaded images and existing products in the database, and recommends similar products.
It uses an Item-Based Collaborative Filtering technique to provide personalized product recommendations based on image recognition.
This repository demonstrates various recommendation techniques, including user-based and item-based collaborative filtering, and leverages different data sources such as movie ratings, app usage, location, and image recognition to deliver personalized product recommendations.
