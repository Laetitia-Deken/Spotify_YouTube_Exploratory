# Spotify YouTube Exploratory

![Spotify YouTube Exploratory](spotify_youtube.jpg "Spotify YouTube Exploratory")

## Dataset

Link to the Dataset : https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube

Link to my Dashboard in Looker Studio : https://lookerstudio.google.com/u/0/reporting/1ea39cb5-11a5-45d9-97cb-44bf5ced25ee/page/z3DXD/edit

## Content

It includes 26 variables for each of the songs collected from Spotify. These variables are briefly described next:

- Track: name of the song, as visible on the Spotify platform.
- Artist: name of the artist.
- Url_spotify: the Url of the artist.
- Album: the album in wich the song is contained on Spotify.
- Album_type: indicates if the song is relesead on Spotify as a single or contained in an album.
- Uri: a spotify link used to find the song through the API.
- Danceability: describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.
- Energy: is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.
- Key: the key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
- Loudness: the overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.
- Speechiness: detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
- Acousticness: a confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
- Instrumentalness: predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
- Liveness: detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
- Valence: a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
- Tempo: the overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
- Duration_ms: the duration of the track in milliseconds.
- Stream: number of streams of the song on Spotify.
- Url_youtube: url of the video linked to the song on Youtube, if it have any.
- Title: title of the videoclip on youtube.
- Channel: name of the channel that have published the video.
- Views: number of views.
- Likes: number of likes.
- Comments: number of comments.
- Description: description of the video on Youtube.
- Licensed: Indicates whether the video represents licensed content, which means that the content was uploaded to a channel linked to a YouTube content partner and then claimed by that partner.
official_video: boolean value that indicates if the video found is the official video of the song.

## Overview

Welcome to my Spotify and YouTube Data Analysis project! 

The purpose of this analysis is to reveal important information about data from two famous music streaming platforms: Spotify and YouTube.

Using exploratory data analysis, let's discover together sometimes unexpected relationships between views, likes, comments and many other variables to display music trends!

Which artists and albums are the most popular on these two platforms? 

## Project highlights

📌 **Data Preparation:** Rigorously cleaned and prepared the dataset, ensuring data quality and integrity for robust analysis.

📌 **Initial Exploration:** Engaged in initial data exploration during EDA to gain a deep understanding of variables and distributions.

📌 **Data Cleaning:** Employed advanced data cleaning techniques to handle missing values, outliers, and inconsistencies, ensuring accuracy in analysis.

📌 **Data Visualization:** Utilized Matplotlib and Seaborn to create compelling visualizations, revealing hidden trends in Spotify and YouTube data.

📌 **Meaningful Conclusions:** Derived insights to shed light on artist popularity, likes, views, streams, album types, and correlations between variables.

## Insights

From the Spotify and YouTube Exploratory Data Analysis, several intriguing insights emerged:

📌 The artist "Macklemore & Ryan Lewis" garnered a remarkable 10.23 billion views, securing the top spot. "Justin Bieber" followed closely with 10.12 billion views, while "BTS" held third place with 10 billion views.

📌 "BTS" emerged as the most liked artist, amassing an impressive 14 million likes. "Blackpink" secured the second position in likes. In terms of streams, "Post Malone" led with 1.2 billion streams, closely followed by "Ed Sheeran" with 1.74 billion streams.

📌 The dominant album type was "Album," accounting for 75% of the data, surpassing compilations and singles.

📌 The album "Album Vida" garnered the highest number of likes at 120 million. "See You Again" and "The Heist" followed with 80 million and 74 million likes, respectively.

📌 "Album BE" stood out as the most commented album, along with "Map of the Soul." Interestingly, a higher number of comments correlated with lesser-known albums. However, "Vida" defied this trend, accumulating higher likes and comments, signalling a positive response.

📌 A correlation existed between speechiness and tempo, with faster tempos typically associated with higher speechiness.

📌 Songs with higher speeches often displayed lower instrumentals, indicating an emphasis on lyrics and vocal delivery, as seen in spoken word or rap genres.

## Conclusion

The Spotify and YouTube Data Analysis project provides valuable insights into music streaming trends and artist performance. Based on the analysis of the provided data, the following conclusions can be drawn:

📌Artist Popularity: "Macklemore & Ryan Lewis" emerged as the most viewed artist, amassing a staggering 10.23 billion views. "BTS" secured the highest number of likes with 14 million likes. "Post Malone" claimed the top position in terms of streams with 1.2 billion streams. These findings highlight the popularity and influence of these artists in the music streaming landscape.

📌Album Types: The majority of the data (75%) corresponds to the "Album" type, indicating that albums are the preferred form of music consumption among users. This insight can guide music platforms and artists in prioritizing album releases and promotional efforts to cater to user preferences.

📌Likes and Comments: "Album Vida" received the highest number of likes, accumulating 120 million likes. Additionally, it stood out as the most commented album, indicating strong engagement and positive feedback from users. These findings suggest that "Album Vida" has resonated well with the audience and has generated significant user interaction.

📌Speechiness and Instrumentalness: A correlation was observed between speechiness and tempo, where songs with faster tempos exhibited a higher level of speechiness. Furthermore, songs with higher speechiness tended to have a lower level of instrumentalness. This implies that genres or styles emphasizing vocal delivery, such as spoken word or rap, tend to have faster tempos and lower emphasis on instrumental elements.

📌Conducted Data Analysis with Python: Leveraged Python libraries including Pandas, NumPy, Matplotlib, and Seaborn to perform comprehensive data analysis tasks.
Derived Insights and Conclusions: Synthesized findings from the analysis by utilizing a database, and generated meaningful insights and conclusions. These insights contributed to informed decision-making and provided valuable recommendations based on the analyzed data
In conclusion, the Spotify and YouTube Data Analysis project provides valuable insights into artist popularity, album preferences, user engagement, and musical characteristics. These insights can be leveraged by music streaming platforms, artists, and marketing teams to make informed decisions regarding content promotion, audience targeting, and playlist curation.

