# Movie-Recommender-System
You can view at :https://movie-rcmd-sys.herokuapp.com/ <br>
Dataset :https://www.kaggle.com/tmdb/tmdb-movie-metadata

What Are Recommendation Systems in Machine Learning?
Recommender systems are the systems that are designed to recommend things to the user based on many different factors. These systems predict the most likely product that the users are most likely to purchase and are of interest to. Companies like Netflix, Amazon, Youtube etc. use recommender systems to help their users to identify the correct product or movies for them. 
 
The recommender system deals with a large volume of information present by filtering the most important information based on the data provided by a user and other factors that take care of the user’s preference and interest. It finds out the match between user and item and imputes the similarities between users and items for recommendation. 
 
Both the users and the services provided have benefited from these kinds of systems. The quality and decision-making process has also improved through these kinds of systems

Types of recommender system :
1. Content-Based Recommendation System  (we choose this for our project)
 It is another type of recommendation system which works on the principle of similar content. If a user is watching a movie, then the system will check about other movies of similar content or the same genre of the movie the user is watching. There are various fundamentals attributes that are used to compute the similarity while checking about similar content.

Eg: tags



2. Collaborative filtering:
To address some of the limitations of content-based filtering, collaborative filtering uses similarities between users and items simultaneously to provide recommendations. Collaborative filtering models can recommend an item to user A based on the interests of a similar user B

3.Hybrid : - Mixture of above two 

Project Flow :
Steps: 
Step 1: Get Data
Step 2: Preprocessing
Step 3: Model build
Step 4: Convert into website
Step 5: Deploy

LOGIC in Preprocessing :
Convert Every Movies Tags to Vectors
So every movie vector will be there in 3D space.
Find nearest vector for recommending  

We use text vectorization 
The process of converting words into numbers are called Vectorization.

Processing natural language text and extract useful information from the given word, a sentence using machine learning and deep learning techniques requires the string/text needs to be converted into a set of real numbers (a vector) .

After the words are converted as vectors, we need to use some techniques such as Euclidean distance, Cosine Similarity to identify similar words

Smaller the angle, the higher the similarity” — Cosine Similarity

Technique used for text vectorization  - Bag of words.
A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things:

A vocabulary of known words.
A measure of the presence of known words
The model is only concerned with whether known words occur in the document, not where in the document

Refer for more : 1.https://towardsdatascience.com/understanding-nlp-word-embeddings-text-vectorization-1a23744f7223
2.https://machinelearningmastery.com/gentle-introduction-bag-words-model/
