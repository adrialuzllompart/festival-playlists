# festival-playlists
## TM Hack Day 2020

I love music festivals. Every year I go to 2-4 of them and for each one I manually go through this process:

- When a festival releases its lineup, I go to the festival website and for each band / artist I
- Go to setlist.fm and look up the average setlist for the artist’s current tour i.e. what songs do they normally play live
- Go to Spotify and add those songs to a playlist

Although I’m quite quick at it now after having done this many times, it still takes me a good few hours per festival (big festivals have more than 200 bands) and I end up mentally exhausted. So for a long time I’ve wanted to have a go at automating this process.

The original idea was to:
1. Scrape the festival website (e.g. Primavera Sound) to get all the names
2. Use the setlist.fm API to get the setlists
3. Use ths Spotify API to create the playlists and add all the songs.

However, I’m not very happy with the first point since it would mean it would only work for Primavera Sound (and only until they made changes to their website). Hence, I’ve decided that today I’m going to focus on the API bits because if I can figure that out, then I could always copy-paste the names into a text file and then use the APIs. Although this wouldn’t be 100% automated, it would already reduce the time it takes me to go through this process from a few hours to a few minutes (and I could use it for any festival).
