#ML Recommendation Griffind

##About this Repositories
ths repositories contain API, Machine Learning Models, and Datasets that are used in Bangkit Product Capstone Project "Griffind".
Grifind/ Griya finder is a recommendation application for finding the nearest lodging and as a forum for users to exchange information about griya or lodging

##About the Model
There are 2 model that are used in Griffind:
1. knn_model : the model that is used to find the nearest griya from the user location
2. griya_recommendation_model : the model that is used to recommend griya based on the ratings

###knn_model
This model retrieves the user's location based on the coordinates (latitude and longitude) then the model will process it and output the nearest griya name from the user's location. This model uses scikit_learn K-nearest-neighbour to predict the nearest griya

###griya_recommendation_model
this model retrieves the user id's then the model will process it and output the recommended griya based on the user's rating and other users ratings on the griya in the dataset. the output will be 3 recommended griya and the corresponding user id's 

##Deployment
We use Flask as our deployment option. the API retrieves data in JSON format and output the recommendation in JSON format.

