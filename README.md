## Nick Elias

# Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts

## Song Lyrics Sentiment Analysis
This project involves performing sentiment analysis on song lyrics using the spaCy library and the spaCyTextBlob extension. The project pulls song lyrics from the lyrics.ovh public API, saves them as JSON files, and then performs sentiment analysis on the lyrics to assess their polarity (i.e., whether the sentiment of the lyrics is positive or negative).

## Features
* API Integration: Fetch song lyrics from the lyrics.ovh API.
* JSON File Storage: Save the fetched lyrics into JSON files for future analysis.
* Sentiment Analysis: Use spaCy and spaCyTextBlob to analyze the polarity of the lyrics.
* Polarity Scores: Calculate the sentiment polarity for each song, with a score range from -1.0 (negative sentiment) to 1.0 (positive sentiment).

## Usage
1. Fetch Lyrics and Save to JSON:
Run the script to fetch lyrics for a specific song and store them in a JSON file. You can change the artist and song name in the code to fetch different songs.

2. Perform Sentiment Analysis:
Once you have the lyrics stored in a JSON file, you can use the analyze_lyrics_sentiment() function to analyze the sentiment of the lyrics. The function returns the polarity score, which indicates whether the sentiment is positive or negative.

3. Interpretation of Sentiment:
The polarity score will be between -1.0 (negative sentiment) and 1.0 (positive sentiment). Based on the score, you can interpret the overall emotional tone of the song's lyrics.

## Example Songs
In the code, we analyze the following songs:

* "Creep" by Radiohead
* "Happy" by Pharrell Williams
* "Where'd All the Time Go?" by Dr. Dog
* "Shake It Off" by Taylor Swift

## Files
* lyrics_data.json: JSON file containing the lyrics of the song.
* creep_lyrics.json, happy_lyrics.json, whered_all_the_time_go_lyrics.json, shake_it_off_lyrics.json: Example JSON files with lyrics for analysis.


## Commentary
The polarity score ranges from -1.0 (negative sentiment) to 1.0 (positive sentiment).
Positive values indicate that the song's lyrics convey positive emotions, while negative values suggest more negative emotions.