# README

The purpose of this project is to analyze Taylor Swift's lyrics sentiment evolution.


## instruction

1. install spotipy

in terminal, type
````
pip install spotipy --upgrade
````

2. get your Spotify credentials in [Spotify My Dashboard](https://developer.spotify.com/dashboard). This project will be using [Client Credentials Flow](https://developer.spotify.com/documentation/web-api/tutorials/client-credentials-flow)

3. Create a json file to store your credentials. This project will read credentials from a file called 'spotify_credentials.json' in the below format:
````
{"spotipy_client_id":"your-client-id",
"spotipy_client_secret":"your-client-secret"}

````

