![Screenshot 2024-11-08 at 11 17 28 PM](https://github.com/user-attachments/assets/25e8d8e6-7729-4cb8-b558-1b3e66428cb6)# Exploratory Data Analysis
of Spotify Songs on year 2023

### **Introduction**

It is an activity made to explore the covered topics of our whole session for the past few meetings. In order for me to be able to create this program, I personally asked some of my blockmates who has an advanced skills than me. I also seek help to Chatgpt and it did gave me an opportunity to understand more about the things I failed to understand before. 

### **Answers to the Guide Question**

### Overview of Dataset
- #### How many rows and columns does the dataset contain?
  - ![Screenshot 2024-11-08 at 11 17 28 PM](https://github.com/user-attachments/assets/e164ab4f-67e5-4960-985c-4d9f7b6054d7)
##### **The size below the dataframe is shown. It is stated that the rows are 953 and the columns are 24.**
- #### What are the data types of each column? Are there any missing values? 
  ![Screenshot 2024-11-08 at 11 21 15 PM](https://github.com/user-attachments/assets/627f1f8e-15f1-4428-a4ff-62139286b3ba)
![Screenshot 2024-11-08 at 11 21 58 PM](https://github.com/user-attachments/assets/baf301ab-f074-4a60-9064-28589379bb86)
##### **The image given above shows the different list of the datatype used. Also, since the boolean function return True, it means there is a missing value for the dataset.**

### Basic Descriptive Statistics

- ####  What are the mean, median, and standard deviation of the streams column?
  - ##### The mean of the streams is equal to 514137424.93907565
  - ##### The median of the streams is equal to 290530915.0
  - ##### The sd of the streams is equal to 566856949.0388832

- #### What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers?
  - Track trends from 1930's to year 2000's are almost constant. Starting from year 01' tracks started to grow. It will be seen in the graph that in year 2022, many artists generated a track which makes it the year where many tracks bloomed. 

### Top Performers

- #### Which track has the highest number of streams? Display the top 5 most streamed tracks.
  - Top 5 were Blinding Lights by The Weeknd, Shape of You by Ed Sheeran, Someone You Loved by Lewis Capaldi, Dance Monkey by Tones and I and lastly, Sunflower - Spider-Man: Into the Spider-Verse by Post Malone, Swae Lee   
- #### Who are the top 5 most frequent artists based on the number of tracks in the dataset?
  - Top 5 artists (from top 1 to top 5) were Taylor Swift, The Weeknd, Bad Bunny, SZA, Harry Styles
### Temporal Trends
- #### Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
- #### Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?
- Most trackls are released in Janaury, Next in June. 


### Genre and Music Characteristics
- #### Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most?
- #### Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?

### Platform Popularity

- #### How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compareWhich platform seems to favor the most popular tracks?
  
### Advanced Analysis

- #### Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
- #### Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts.




