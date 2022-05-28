# Content-based-Movie-Recommendation-System
Content based Movie Recommendation System Used to Suggest Movie to user based their searches

![Python](https://img.shields.io/badge/Python-3.10.4-blueviolet)
![library](https://img.shields.io/badge/Framework-streamlit-red)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

Content Based Recommender System recommends movies similar to the movie user likes .It Suggest 5 Movies based on their recommendation.

The details of the movies(title, genre, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API.

# Frontend 

![image](https://user-images.githubusercontent.com/84464407/170840259-7396e77e-9a73-48b9-8cda-0ec8784962a1.png)

## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

## Steps for run the project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/Movie-Recommendation-System-with-Sentiment-Analysis/blob/master/requirements.txt) file with the command `pip install -r requirements.txt`
3. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
4. Open your terminal/command prompt from your project directory and run the file `app.py` by executing the command `streamlit run app.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Hurray! That's it.

## Similarity Score : 

   How does it decide which item is most similar to the item user likes? Here come the similarity scores.
   
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   
   ## Source of the Dataset
   https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv


