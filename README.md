# movie-recommender-system-tmdb-dataset
A content based movie recommender system using cosine similarity
Movie Recommender system. 
Ecommerce, saavn, YouTube, spotify, Instagram, Netflix, Facebook. In an offline system, we go to a shop and ask for shop keeper to show us a pair of jeans . Then customer asks for other similar types. How does the shopkeeper show the customers a similar style? 
Types of recommendation system: 
Content based recommendatiom system:
Content similarity. Example ur listening to a romantic song , the next song would also mostly be a romantic one not a rock song. Tags get created for the things. 
Collaborative filtering based:
This is based on the users interest and behavior. Depends on the users similarity. Example posts that are recommended to ur friend would be recommended to you. 
Steps:
Data preprocessing
Model building
Website - convert to product. 
Deploy
Main steps:
Movie_id, title, tags
Text Vectorization/ bag of words technique: convert the text to vectors
Grab the closest vectors in the two d space. 
Each movie has a tag. 
Around 5000 movies in the dataset. 
Concatenate all the tags to make a big string that contains large text. 
Find the 5000 most common words. 
For each movie find the frequency of each word example action, future, etc. 
Stop words: are from a in to is 
The meaning of thr sentence does not change if these stop words are removed. 
Pip install nltk
Examples:
Stemming: loving, loved, love : love is the final stemmed word. 
Dancing, danced, dance : dance is the final stemmed word. 

Calculate the distance of the movies vector with the other movie vectors. 
Don't calculate the euclidean distance is not a reliable measure. Not recommended. Calculate the angle or the cosine distance. Theta between two vectors. 
Distance is inversely proportional to similarity. 
Sci kit learn contains certain libraries
Pickle library
