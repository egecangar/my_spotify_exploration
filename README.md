# Spotify Analysis Project

It is the term project of my CS 210 course.

## Setup

### Python

This code is written in the Python programming language.

While versions of Python may come with your OS, I used [pyenv](https://github.com/pyenv/pyenv) to install the latest version.

This README assumes the latest version of your Python install is run using `python`

### Clone this repository

'gh repo clone egecangar/my_spotify_exploration'

### Install the Spotipy library

Install the client for the Spotify Web API for Python:

`pip install spotipy`


### Install the scikit-learn libraries

If you want to make calculations on Machine Learning:

`pip install scikit-learn`


`pip install scikit-learn matplotlib`

### Setup your credentials file

Create a file called `credentials.config`

Go to the [Spotify for Developers Dashboard](https://developer.spotify.com/dashboard/applications) and create an app.

Then add the following lines to `credentials.config`

```
[DEFAULT]
SPOTIFY_CLIENT_ID = xxx
SPOTIFY_CLIENT_SECRET = yyy
SPOTIFY_REDIRECT_URI = https://example.com/callback
```

### Add a refresh token to your config file

Then add a refresh token to the config file by running

`python get_refresh_token.py`

You'll then see in your `credentials.config` the added line

`SPOTIFY_USER_REFRESH = aaa`

## Other dataset

I've included also my favourite playlist.The name of my playlist is Study.

My data set is about my Spotify playlist. It includes 309 songs in 26 columns.

**HTTPS:** https://github.com/egecangar/my_spotify_exploration.git

**Columns:**  
Below, you can find all the set of features, provided in the dataset:

1. **Song:** The name of the track.
2. **Artist:** The name of the artist or group that performed the song.
3. **Popularity:** A numerical measure of the song's popularity.
4. **BPM (Beats Per Minute):** The tempo or speed of the song in beats per minute.
5. **Genres:** The musical genres associated with the song.
6. **Parent Genres:** The broader or parent musical genres of the song.
7. **Album:** The name of the album containing the song.
8. **Album Date:** The release date of the album.
9. **Time:** The duration of the song in minutes and seconds.
10. **Dance:** A numerical value indicating danceability.
11. **Energy:** A numerical value representing the energy level of the song.
12. **Acoustic:** A numerical value indicating the acousticness of the song.
13. **Instrumental:** A numerical value indicating the instrumentalness of the song.
14. **Happy:** A numerical value representing the mood or happiness of the song.
15. **Speech:** A numerical value indicating the presence of speech or lyrics in the song.
16. **Live:** Indicates if the song is a live recording (1 for live, 0 for studio).
17. **Loud:** A numerical value indicating the loudness of the song.
18. **Key:** The musical key in which the song is composed.
19. **Time Signature:** The time signature of the song.
20. **Added At:** The date or timestamp when the song was added to the dataset.
21. **Spotify Track Id:** Unique identifiers assigned to each track by Spotify.
22. **Album Label:** The name of the record label associated with the album.
23. **Camelot:** Information about the musical key or tonal center of the song.
24. **Spotify Track Img:** URLs or references to images associated with the Spotify tracks.
