# Simple-Spotify-Now-Playing
A simple web page with Node Red to show Spotify now playing song / top artist when not playing

## Description
A very simple webpage for showing the now playing song and album art from a spotify account based on Node Red. Includes buttons to pause and skip (although does not work when playing on certain devices e.g. Sonos)

![example page](https://github.com/mwinterstorm/Simple-Spotify-Now-Playing/blob/main/Readme%20images/page.jpg)

### Node Red Flows
![Node Red Flows](https://github.com/mwinterstorm/Simple-Spotify-Now-Playing/blob/main/Readme%20images/flows.jpg)

## To use
1. Install Node Red
2. Install required nodes as set out in [required_nodes.md](https://github.com/mwinterstorm/Simple-Spotify-Now-Playing/blob/main/required_nodes.md)
3. Import [spotifynodered.json](https://github.com/mwinterstorm/Simple-Spotify-Now-Playing/blob/main/spotifynodered.json) into Node Red
4. Set up [Spotify Developer Account](https://developer.spotify.com/dashboard/) and new project 
5. Authorise the Spotify node in Node Red using Project ID and Secret and the [Scopes here](spotify_scopes.md)
6. Now playing web page is available at http://[your.nodered.ip]/spotify
7. Uses basic http authorisation [user:admin, password:admin]

## Options
You can:
1. Change web page in Web Request node

## To do
1. Fix top artists / top tracks screensaver
1. Slow down screensaver update 
