# YoutubeGeneratedPlaylist
A script that takes songs from selected Spotify playlist and generates a YouTube playlist (based on the songs saved in the Spotify playlist)
## Table of Contents 
* [Technologies](README.md#technologies)
* [Setup](README.md#localsetup)
## Technologies 
* [YouTube Data API v3](https://developers.google.com/youtube/v3)
* [Spotify Web API ](https://developer.spotify.com/documentation/web-api/)
* [Requests Library v 2.22.0](https://docs.python-requests.org/en/master/)
* [Youtube_dl v 2020.01.24](https://github.com/ytdl-org/youtube-dl/)
## LocalSetup
*  Install all dependencies 
  `pip install -r requirements.txt`
* Collect your Spotify User ID and Oauth Token and add it to secret.py file
* To Collect your User ID, Log into Spotify then go here: [Account Overview](https://accounts.spotify.com/en/login?continue=https%3A%2F%2Fwww.spotify.com%2Fus%2Faccount%2Foverview%2F) and its your **Username
*  To Collect your Oauth Token, Visit this url here: [Get Oauth](https://developer.spotify.com/console/post-playlists/) and click the **Get Token** button

