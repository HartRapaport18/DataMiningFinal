# DataMiningFinal

Using Spotify's Million Playlist Dataset (https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge) and API (https://www.rcharlie.com/spotifyr/), we analyze whether human-measured song similarity (as seen in playlist co-occurence) is related to computer-measured song similarity (as measured by the audio features found in the get_track_audio_features function). We find that they are related to a certain degree--each of the four models we fit (linear, LASSO, PCR, GBM) performed better than a "random" baseline model in terms of RMSE and sMAPE. However, pairs of songs that have the highest co-occurence are hard to predict because that is premised on sharing an artist or theme that is not captured by audio features. We recommend more study to find pairs of songs that are similar, but not too similar.


Code (.Rmd) and output (.pdf) are listed above.
