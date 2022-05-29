
# ABOUT MOVIES TIME!
Movies time is an AI based web application in which you can search for any Hollywood Movie. This application will provide all the information related to that movie, does sentiment analysis on the movie reviews and the most interesting part, this application will provide you the top 10 movie recommendations based on your search.

ReactJS was used for frontend.This application uses Content Based Movie Recommendation to recommend movies to the user.TMDB API was used to retrieve all the information related to the movie and its cast. Web Scraping was done on IMDB website to get the reviews related to the searched movie. Sentiments analysis is done using a machine learning model trained on a sample of IMDB Dataset.


## How to generate TMDB API Key?
1. Login to you your tmdb account: https://www.themoviedb.org/ or create one if you dont have.
2. Then open https://www.themoviedb.org/settings/api link and create your api key by filing all the necessary information.
3. IMPORTANT: After generating the TMDB API KEY, replace "ENTER YOUR TMDB_API_KEY" with your generated key in the API and FRONTEND code.
TMDB API End Points
## Flask API end points
TO GET MOVIE RECOMMENDATION 
        
        Data to be sent in POST request: { movie_name:"The Avengers", number_of_recommendations:"10" }

Data Returned by the API in JSON format: { input_movie:{ movie_id:TMDB_MOVIE_ID }, recommendations:[
        
        
        {
            rank:1,
            movie_id:TMDB_MOVIE_ID
        },
        {
            rank:2,
            movie_id:TMDB_MOVIE_ID
        },
        {
         rank:3,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:4,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:5,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:6,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:7,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:8,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:9,
            movie_id:TMDB_MOVIE_ID
        },
         {
         rank:10,
            movie_id:TMDB_MOVIE_ID
        },
    ]
}
## To get Movie Reviews with Sentiments:


Data to be sent in POST request:
{
    movie_imdb_id:"MOVIE_IMDB_ID"
}

Data Returned by the API in JSON format:
[
   
   
    {
        id: 1,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
    {
        id: 2,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 3,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id:4,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 5,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 6,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 7,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 8,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 9,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },
     {
        id: 10,
        content: "THE REVIEW",
        sentiment: "SENTIMENT FOR THE REVIEW"
    },

]
## Steps to run the React Project
1. Clone or download the repository in your local machine.
2. Open command prompt in the following folder client
3. Install all the npm packages

        npm install
    

4.Run the file using the command. 

      npm start
## Steps to run the Flask API
1. Clone or download the repository and open command prompt in API folder.
2. Create a virtual environemt.
      
         mkvirtualenv environment_name

3. Install all the dependencies

       pip install -r requirements.txt

4. Run the app.py file

         python3 app.py

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akash-singwal-46913622a/)

## Github profile link

https://github.com/akash13072002


