# SpotifyToApple
Spotify to apple music playlist conversion

A Work in progress currently dealing with two major issues: 
- Composer information is required to mimic a proper playlist file. Unable to find infroamtion through ITunes api.
- Itunes api has set limit for community request at 1 request every 3 seconds, making the retrival process slow.

What it can do:
- Using spotify API and callback can access user music library lisitng all playlists
- once a playlist is selcted all songs in the playlist are dispalyed in a list as embeded spotify players
- beside the spotify list an apple music embeded player list is created, with any 403 errors repalced with a rick roll.
