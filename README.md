
# SPOTIFY DATA ANALYSIS

This code performs an analysis of Spotify tracks data to gain insights into various aspects of music, such as popularity, genre, duration, and correlation between variables. The data is imported from two separate CSV files: 'tracks.csv' and 'SpotifyFeatures.csv'. It is a beginner friendly portfolio project.



##  LIBRARIES USED

To run this script, you need to have Python installed on your system, along with the following libraries:

1. #### [Numpy (version 1.20.1)](https://numpy.org/)
2. #### [Pandas (version 1.2.4)](https://pandas.pydata.org/)
3. #### [Matplotlib (version 3.3.4)](https://matplotlib.org/)
4. #### [Seaborn (version 0.11.1)](https://seaborn.pydata.org/)



## Data Import

The first step is to import the Spotify tracks data from the 'tracks.csv' file using pandas.read_csv(). The data is then examined using 'dataframe_tracks_of_spotify.head()' and 'dataframe_tracks_of_spotify.info()' to check for missing values and get an overview of the data.



## Data Cleaning

The next step is to clean the data by removing unnecessary columns, converting the release date to datetime format, and rounding the duration to seconds. The cleaned data is stored in a new dataframe.



## Data Analysis

The cleaned data is then used to perform various analyses and visualizations to gain insights into different aspects of the music:

1. #### sorted_dataframe: A new dataframe is created by sorting the tracks based on their popularity in ascending order.

2. #### most_popular: A new dataframe is created by selecting the tracks with popularity greater than 90 and sorting them based on popularity in descending order.

3. #### correlation_dataframe: A correlation heatmap is created using seaborn.heatmap() to visualize the correlation between different variables in the data.

4. #### sample_dataframe: A sample of the data is taken to plot the correlation between energy and loudness and between acousticness and popularity.

5. #### total_duration: The total duration of songs per year is calculated and visualized using seaborn.displot() and seaborn.barplot().

6. #### famous: The top 10 genres by popularity are visualized using seaborn.barplot().



## Conclusion

This code provides a basic analysis of Spotify tracks data and can be used as a starting point for further exploration and analysis of the data.
## Tech Stack

**Client:** VS Code, Python, [Kaggle](https://www.kaggle.com/)

