# spotify-to-appleMusic
This repository helps user to transfer their Spotify Playlists, Liked songs to Apple Music.

Approach:
1. Using Exportify, connect your Spotify account and extract the .csv files of playlists which you want to transfer to Apple Music.
2. Run the retrievedIdentifier with those csv files and get the csv files for Apple Music Identifier.
  - Note: If in case, the script fails to lookup the Spotify song on Apple Music, a <Playlist_name>_not_found.csv file will be created, you can use that file to add those songs manually.
3. WIP
