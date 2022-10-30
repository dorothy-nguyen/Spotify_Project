# Spotify Audio Feature Exploration
## by Dorothy Nguyen

## 1. Dataset

> In this Jupyter Notebook, I investigate the dataset which includes audio features of more than 130,000 Spotify tracks retrieved from Kaggle latest updated by April 2019. Dataset is downloaded from Kaggle which originally used the Spotify API to request and pull data. The dataset consists information of artist_names, track_ids, track_names, track's features themself and their popularities specified in this [Spotify API Documentation](https://developer.spotify.com/documentation/web-api/reference/#/).

> With Statistics by Spotify as of Sep 2021, it is currently the world's leading audio streaming subscription service with 381 millions MAUs (montly active users) which offers us a platform of more than 73 millions pieces of tracks and podcasts.

> My assumption is that popular songs may have some characteristics that are different from the less popular ones.

> Over the course of this analysis, I will explore and visualize the data using Python libraries Pandas, Numpy and Matplotlib in order to answer three main research questions:
> > **1. What are the most popular artists and tracks on Spotify over the course of our dataset?**

> > **2. What kinds of properties are associated with songs that have higher popularity ratings?**

> > **3. Are there any relationships between track's features themself and their popularity?**

> Answers to those questions can benefit both Spotify and its customers to get a better understanding of the most significant patterns and trends in the music industry.

## 2. Software requirements
The following versions of libraries were implemented to conduct the project:
- pandas==1.4
- numpy==1.22
- matplotlib==3.5
- seaborn==0.11

## 3. Summary of main findings
I have found some main findings and a few recommendations to make a track publiced on Spotify popular as followed:

**Question 1: What are the most popular artists and tracks on Spotify over the course of our dataset?**
- Most prolific artists are of all time best-known composers of classical music.
- Daddy Yankee- a hit-after-hit artist is the only one who gets the perfect 100 score with his song 'Con Calma' collaborated with Canadian rapper Snow. The song has surpassed 2 billion views on Youtube by 2020.
- Billie Eilish has 11 records which is the highest number of songs in the top 100 most popular tracks. Post Malone, Ariana Grande and Khalid come second with 4 tracks each.

**Question 2: What kinds of properties are associated with songs that have higher popularity ratings?**
- C Minor, C Major and G Major dominate other keys to be the most used musical keys due to convenience and ease to play on piano and guitar.
- Musicians can have a higher chance to make hits on Spotify by composing more energetic, positive and more danceable musical pieces. Generally, higher energy and lower songs out perform low energy and quieter songs.
- Tracks have higher likelihood to be popular if they offer audiences more compelling vocals and ignite the fresh, cheerful and positive feelings in audiences.
- Live performance are less prefered compared to recorded audios when it comes to taste of Spotify customers.
- On average, shorter duration of tracks are expected to give them a higher score of popularity.

**Question 3: Are there any relationships between track's features themself and their popularity?**
- Generally, higher energy and louder tracks have a higher chance to become popular on Spotify than lower energy and quieter tracks.
- Using electonic instruments like electric guitars and keyboards can improve the chance of success for musicians once they release their songs on Spotify platform.

Regards to the limitations of this project, as this was only an exploratory analysis, these findings do not imply any statistical conclusions. The data should be further inspected with proper statistical test in order to drive more potential correlations.

**Check out the full report of my analyzation and presentation for charts and viz via [`Spotify_presentation`](https://github.com/dorothy-nguyen/Spotify_Project/blob/main/Spotify_presentation.pptx)**
