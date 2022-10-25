Music and n8n
My n8n automations for sharing, organizing and enjoying music.

Apache 2.0 License LinkedIn

Music and N8N Automation Flows
This set of N8N flows will let you share, organize and enjoy your music.
Table of Contents
About The Project
The project consists of a set of flows that will let you organize, share and enjoy your music. The flows were created in n8n, an open source automation tool.

(back to top)

Built With
![n8n][n8n]
![JavaScript][JavaScript]
(back to top)

Getting Started
You'll need an n8n account, the desktop application installed or a cloud user account.

Prerequisites
JavaScript basic knowledge
Algorithms basic knowledge
Control flow basic knowledge
Spotify API credentials
YouTube API credentials
Twitter API credentials
Installation
Install n8n at https://n8n.io
Get a free API Key from Spotify https://spotify.com
Get a free API Key from YouTube https://youtube.com
Get a free API Key from Twitter https://twitter.com
Copy the JSON files and open them in n8n (desktop/cloud).
Customize with own credentials and playlist URIs/IDs.
(back to top)

Usage
Brief explanation of each flow:

EmptyPlaylist.json.- This flow will allow you to empty a Spotify playlist. Remove all the tracks and leave the playlist void. May take several executions if the playlist exceeds more than 256 tracks. image

PutTracksInSpotifyPlaylist.json.- This flow will allow you to merge several playlists into a single Spotify playlist. The criteria must be edited as per needed, final result is an Excel file with all the tracks. image

PromoteArtistOnTwitter.json.- This flow will allow you to share a Twitter thread with an artist Spotify playlist link and subsequent top 10 songs, one per tweet including a YouTube video. The criteria must be edited as per needed. image

AlbumsFromSpotifyPlaylist.json.- This flow will allow you to get all the albums represented within a Spotify playlist and store them in a Excel file. The criteria must be edited as per needed. image

ShareAlbumOfTheYearOnTwitterFromFile.json.- This flow will allow you to share a list of albums in Twitter in a thread (Spotify link + popular YouTube videos). The list will be contained in an Excel file (sample file albums2022.xlsx provided). The criteria must be edited as per needed. image

Recommendation: Allow no more than 3 albums per day to avoid consuming all the YouTube API request limit.

SeveralPlaylistsToFile.json.- This flow will allow you to merge several playlists into a single Excel file in order to be exported. The criteria must be edited as per needed. image

DivideSpotifyPlaylistByReleaseYearV2.json.- This flow will allow you to divide a playlist into several playlists. The criteria must be edited as per needed, right now the criteria is release year of the song. image

MargePlaylists.json.- This flow will allow you to merge one playlist into another excluding the duplicated tracks. Perfecto when you found a great playlist from someone else and you need to add the tracks to your own playlist.

image

(back to top)

License
Distributed under the Apache 2.0 License. See LICENSE.txt for more information.

(back to top)

Contact
Your Name - @nelo_1980 - npazymino@gmail.com

Project Link: /npazymino/music_and_n8n

(back to top)
