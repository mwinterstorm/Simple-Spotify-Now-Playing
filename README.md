# Simple-Spotify-Now-Playing
A simple web page with Node Red to show Spotify now playing song / top artist when not playing

## Description
A very simple webpage for showing the now playing song and album art from a spotify account based on Node Red.

Be warned quite hacky at this stage, e.g. reloads whole web page based on calculated time to end of current song. Noticeable if you change or skip a song, won't update until song would have finished.

### Node Red Flows
![Node Red Flows](/Readme images/NodeRed Flows.png)

## To use
1. Install Node Red
2. Install node-red-contrib-spotify using Node Red package manager
3. Import [spotifynodered.json](https://github.com/mwinterstorm/Simple-Spotify-Now-Playing/blob/main/spotifynodered.json) into Node Red
4. Set up [Spotify Developer Account](https://developer.spotify.com/dashboard/) and new project 
5. Authorise the Spotify node in Node Red using Project ID and Secret and the [Scopes here](spotify_scopes.md)
6. Now playing web page is available at [your.nodered.ip]/spotify

## Options
1. Change web page in Web Request node

## To do
1. Automatically pull user account name
2. When nothing playing alternate between Top Artists / Top Songs / Recently Played
