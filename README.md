# Music Recommender and Player

Description
This app provides personalized song recommendations based on a user’s Spotify profile and displays the lyrics of the recommended songs using the Genius API. It also allows users to listen to a 30-second preview of the recommended song via Deezer.

In addition, the app shows the user's top 5 Spotify songs, giving an overview of their current listening preferences. The main goal of this app is to enhance music discovery by integrating various features from multiple music APIs into a single application.

APIs Used
Spotify Web API:

Purpose: Fetch personalized song recommendations and top 5 songs of the user.
Why Chosen: Spotify offers detailed user data, song recommendations, and various other features related to music streaming, making it a central hub for personalized music features.
Genius API:

Purpose: Fetch the lyrics of the recommended songs.
Why Chosen: Genius is a widely-used platform for song lyrics and provides a vast catalog of lyrics from popular music.
Deezer API:

Purpose: Provide a 30-second song preview for the recommended songs.
Why Chosen: Deezer offers free access to music previews, allowing users to quickly listen to the recommended tracks.
How to Use the App
Clone or Download the Project:

Clone the repository or download the project files to your local machine.
Install Required Libraries:

Install necessary Python libraries using the following commands:
bash
Copy code
pip install requests beautifulsoup4 pygame
Set Up Spotify Developer Account:

Go to the Spotify Developer Dashboard and log in.
Create an app and copy the Client ID and Client Secret.
In the app settings, set the Redirect URI (e.g., http://localhost/callback).
Set Up Genius API:

Go to the Genius Developer Portal and create an app to get your Genius API Token.
Set Up Deezer API:

No special setup is needed for Deezer API access as only song previews are used, which are publicly available.
Instructions to Run the App
Set Up API Keys:

Replace the placeholder values in the code with your Spotify Client ID, Spotify Client Secret, and Genius Token.
Authorize the App:

When you run the app, a URL will be printed in the console (or optionally opened in the browser).
Visit this URL, log in with your Spotify account, and authorize the app.
Copy the authorization code from the URL and input it into the console when prompted.
View Your Top 5 Songs:

After successfully logging in, the app will display your top 5 Spotify songs.
Get a Recommended Song:

The app will fetch a song recommendation based on a pre-defined genre (e.g., hip-hop).
It will also fetch the lyrics for the recommended song using the Genius API.
Listen to the Preview:

The app will provide a 30-second preview of the recommended song using Deezer, and it will play directly in your browser or terminal.

