### Collaborative Based Filtering:
		
- Collaborative filtering systems, which are based on user-item interactions.
	
- Clusters of users with same ratings , similar users .
	
- Book recommendation , so use cluster mechanism .
	
- We take only one parameter , ratings or comments .
	
- In short, collaborative filtering systems are based on the assumption that if a user likes item A and another user likes the same item A as well as another item, item B, the first user could also be interested in the second item . 
	
- Issues are :

	- User-Item nXn matrix , so computationally expensive .

	- Only famous items will get reccomended .

	- New items might not get reccomended at all .   

# About this project:

This is a streamlit web application that can recommend various kinds of similar books based on an user interest.

![WhatsApp Image 2023-12-28 at 23 21 17_e996e03d](https://github.com/Kuldeep-Nayak/Book-Recommender-System_Collaborative-based-filtering/assets/138770146/bfb5c667-c2c6-4bfd-9d69-8b0697c8fdc3)


# Dataset has been used:

* [Dataset link](https://www.kaggle.com/ra4u12/bookrecommendation)

# Concept used to build the model.pkl file : NearestNeighbors

1 . Load the data
	
2 . Initialise the value of k

3 . For getting the predicted class, iterate from 1 to total number of training data points

4 . Calculate the distance between test data and each row of training data. Here we will use Euclidean distance as our distance metric since it’s the most popular method. 

5 . Sort the calculated distances in ascending order based on distance values
	
6 . Get top k rows from the sorted array


### This is a team project of 5 members in Skill and Project Lab in 5th semester during B.Tech. CSE.


# Reference 
https://youtube.com/playlist?list=PLkz_y24mlSJa37r2xNDyEgt0Z4ilHtJ07&si=pyTOkQCF2o2n3d95
