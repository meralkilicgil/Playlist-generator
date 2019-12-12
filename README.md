# Playlist-generator
term project


python main.py toptracksbycountry --country=turkey --count=10

run "python main.py" on command prompt to start Flask
firstly vim is open, exit vim then continue

localhost:5000/topTurkey : creates top 50 tracks of turkey with "top tukey" playlist name

localhost:5000/getSimilar/<artist>_<track>_<count>_<name> : creates similar songs 'track' by 'artist'  with number of 'count' to the playlist name 'name'.