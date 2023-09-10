# Movie-Recommendation-System-Project
This project is to recommend movies and it is an ML-based approach to filtering or predicting the user’s film preferences based on their past choices and behaviour.

# Background
What can we say about the success of a movie before it is released? Are there certain companies (Pixar?) that have found a consistent formula? Given that major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success? This is a great place to start digging in to those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.

# Dataset Description
Several of the new columns contain json. You can save a bit of time by porting the load data functions from this kernel.
Even in simple fields like runtime may not be consistent across versions. For example, previous dataset shows the duration for Avatar's extended cut while TMDB shows the time for the original version. There's now a separate file containing the full credits for both the cast and crew. All fields are filled out by users so don't expect them to agree on keywords, genres, ratings, or the like. Your existing kernels will continue to render normally until they are re-run.
If you are curious about how this dataset was prepared, the code to access TMDb's API is posted here.

# TMDB 5000 Movie Dataset: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
# Top Genres :

![image](https://github.com/Prabhat1225/Movie-Recommendation-System-Project/assets/107301804/74f7c70b-e37d-4d2a-9014-c414c6fa77af)

# Tech Used
![Logo](https://logowik.com/content/uploads/images/python.jpg)
![Logo](https://seeklogo.com/images/S/streamlit-logo-B405F7E2FC-seeklogo.com.png)

# Libraries USED
* Numpy
* Pandas
* Sklearn
* Pickle
# Deployment

To deploy this project run

```bash
  streamlit run app.py
```
  ## Cosine Similarity

![Logo](https://www.oreilly.com/api/v2/epubs/9781788295758/files/assets/2b4a7a82-ad4c-4b2a-b808-e423a334de6f.png)

# Some UI are 
![Screenshot (705)](https://github.com/Prabhat1225/Movie-Recommendation-System-Project/assets/107301804/cf530cf1-1c9f-4c97-a796-81621edfd9b1)

![Screenshot (706)](https://github.com/Prabhat1225/Movie-Recommendation-System-Project/assets/107301804/4bd2c42c-ed66-41e8-ac87-624f8adf049d)

![Screenshot (707)](https://github.com/Prabhat1225/Movie-Recommendation-System-Project/assets/107301804/a564044a-529a-4e04-9cdd-f2b34f456ce4)
