# festival-playlists
## TM Hack Day 2020

I love music festivals. Every year I go to 2-4 of them and for each one I manually go through this process:

- When a festival releases its lineup, I go to the festival website and for each band / artist I
- Go to setlist.fm and look up the average setlist for the artist’s current tour i.e. what songs do they normally play live
- Go to Spotify and add those songs to a playlist

Although I’m quite quick at it now after having done this many times, it still takes me a good few hours per festival (big festivals have more than 200 bands) and I end up mentally exhausted. So for a long time I’ve wanted to have a go at automating this process.

The original idea was to:
1. Use the Songkick API to get all the names playing the festival
2. Use the Setlist.FM API to get the setlists
3. Use the Spotify API to create the playlists and add all the songs.
