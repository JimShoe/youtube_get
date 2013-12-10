youtube_get
-----------

Podcast like script which uses youtube-dl and wget to download videos from channels.

Config
------
You will need to edit a few variables inside the script.

shows: This is an array of youtube channels you want to download.
DOWNDIR: Directory to download each episode.
LOG: Log of downloaded episodes.
CATCHUP: Number past episodes to download.

Notes
-----
There is a 5min wait after downloading each episode.  This is so that Youtube doesn't deny 
you.
