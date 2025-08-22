# Spotify-Manager

To run on your own, [create a Spotify app ↗](https://developer.spotify.com/documentation/web-api/concepts/apps), then make a .env file with the following information:

SPOTIPY_CLIENT_ID = ...  
SPOTIPY_CLIENT_SECRET = ...  
SPOTIPY_REDIRECT_URI = http://127.0.0.1:9090  
  
Yes this is doing too much, that's why I'm making a web app so you only need to click a button to do all this
  
------- 
  
Main functions:  
    - merge_playlists : creates new merged playlist without duplicates  
    - clean_out_playlist : creates new playlist with already-saved tracks removed  
    - save_queue : saves user's added queue to a playlist  

Code will prompt you for which one you want to do

-------  
    
**Web app coming**  
