# Movie-Recommender-Systems
Predicting movies using content based filtering and deploying the model using streamlit.
##STEPS INVOLVED
###Data gathering and pre-processing
* In this TMDB 5000 movies dataset is used which is available in kaggle.
* I have dropped the features apart from genre, overview, title, cast and crew and combined them into one feature named 'tags'.
###Vectorizing and checking similarity
* Converting tags column to  vectors.
* Calculating the distances between movies using cosine similarity.
###Recommendation
* Giving the names of top 5 movies which are most similar.
* Lesser the distance , more is the similarity.
###Deploying
* Making a simple web page which gives top 5 similar movies and their posters using streamlit.

# Output
The dark knight Rises
![Screenshot_20221224_100315](https://user-images.githubusercontent.com/67310375/227574855-d8f1e8fe-2dbd-47c0-85eb-a572af132a5c.png)




