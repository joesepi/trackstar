TrkStr


Motivation:
----------
To be able to easily create playable playlists for my band

Experience:
----------
on page load, you would have the media player on the left and playlists on the right.
There should be two groupings in the playlists section: Media/Playlists

Media section
Navigating the Media section is like navigating the media directory (band/album/tracks) and you can initiate a 'player' at any level. (for example, you can play all tracks from all albums of one band or select a specific album or even a specific track. It would be good to just play all of the music in the media directory as well.)

Playlists section
You can create JSON objects that represent playlists.

I would also like to include metadata in the JSON files, like description or

Shuffle would be nice, but can be phase 2


Dir Structure:
-------------
/media
  /band (should be able to play/shuffle all of a bands tracks)
    /album (each album should have json that can be played)
      - track(s)
/assets
  /js
  /css
/playlists (JSON)
  - next-gig.json
  - acoustic-options.json
  - songs-to-focus-on.json

