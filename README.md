![](images/spotify%20100_readme.PNG)
# Spotify Project
### A group project with the University of Birmingham Data Analytics Bootcamp (December 2021)

Spotify is an online streaming platform founded by Daniel Ek and Martin Lorentzon, in mid-2006. Spotify is currently the largest music streaming service across the globe, with almost 400 million monthly active users. 

The aim of this project was to explore what makes a song popular by analysing the top 100 streamed songs on the streaming platform Spotify. In order to collate the required data, the Spotify API was utilised to return JSON metadata about the artists’ name, tracks, streams (millions), followers, and various audio features, directly from the Spotify data catalogue. 

### Collating the Data

The final file was created using the spotify API to pull two dataframes:

 - [Track information](https://github.com/Amina-H1/spotify-project/blob/main/tracks.csv), pulled from a Spotify playlist of the top 100 streamed songs. This contains basic track information, such as artist/album name and release dates.
 - [Audio features](https://github.com/Amina-H1/spotify-project/blob/main/features.csv), pulled from the API's audio features function. This covers a wide range of information created using Spotify's own algorithms, such as danceability, acousticness, energy and valence (see Table 1, below). 

Finally, the number of streams was collected from [Wikipedia](https://en.wikipedia.org/wiki/List_of_most-streamed_songs_on_Spotify).
![](images/table1.PNG)
### Findings 1: Duration, Followers and Streams 
