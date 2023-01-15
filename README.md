# YOUTUBE-TRENDING-VIDEO-ANALYSIS
A Web App that analyzes YouTube trending videos to identify characteristics that make a video trend and provides a predictor that determines the trending status of a video based on user-provided inputs. 


### Project Overview:

- Develop a web application for analyzing YouTube trending videos and identifying characteristics that make a video trending.
- Use CRISP-DM methodology.
- Final product: web application that predicts the trending status of a video and provides statistics and analysis of trending videos and channels.

### Methodology:

- CRISP-DM methodology: business understanding, data understanding, data preparation, modeling, evaluation, and deployment.
- Data collection: Kaggle and YouTube API.


### Data Preparation:

- Generate additional columns to enhance the structure of the data.
- Perform data cleaning process to remove irrelevant or unnecessary data.


### Modeling:

- Train models using cleaned data.
- Make predictions on the trending status of videos.


### Evaluation:

- Web application that allows users to input specific video information and receive a prediction on whether the video will trend or not.
- Provide statistics and analysis on trending videos and channels.


### IMPLEMENTATION:

The final product of this project is a web application called YT App, which has three main parts: "Predictor", "Trending Channel and Analytics", and "Trending Video Analysis".

#### Predictor:

- Uses Random Forest as a classifier.
- Contains three input fields: view count, like count, and comment count.
- The results are in the form of trending or non-trending.

<img src="/WebApp_screenshots/predictor.JPG" alt="predictor.JPG">


#### Trending Channel and Analytics:

- Allows users to select a channel from a drop-down list.
- Shows the channel category and view channel link.
- Displays channel analytics: view count, subscriber count, and video count.
- Table shows trending year, trending month, trending video, and title sentiment.
- Recommender system recommends top 3 channels based on selected channel.

<img src="/WebApp_screenshots/Trending Videos Analysis.JPG" alt="Trending Videos Analysis.JPG">

<img src="/WebApp_screenshots/Trending Channel and Analytics.JPG" alt="Trending Channel and Analytics.JPG">
