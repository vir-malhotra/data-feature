# Music Recommender and Player

# **Spotify Song Recommender & Lyrics Display App**

## **Description**

This app provides personalized **song recommendations** based on a user's Spotify profile and displays the **lyrics** of the recommended songs using the Genius API. It also allows users to listen to a **30-second preview** of the recommended song via Deezer. Additionally, the app shows the user's **top 5 Spotify songs**, helping users explore their current favorites.

### **Features**
- Fetches a personalized song recommendation based on the user's Spotify profile and a pre-defined genre.
- Displays the user's **top 5 Spotify songs**.
- Retrieves the **lyrics** of the recommended song from Genius.
- Plays a **30-second preview** of the recommended song via Deezer.

---

## **APIs Used**

### 1. **Spotify Web API**
   - **Purpose**: Fetches personalized song recommendations and the user's top songs.
   - **Why Chosen**: Spotify provides detailed data about user preferences and a robust music recommendation engine.

### 2. **Genius API**
   - **Purpose**: Retrieves song lyrics for the recommended tracks.
   - **Why Chosen**: Genius has a large database of song lyrics, making it a great choice for displaying song information.

### 3. **Deezer API**
   - **Purpose**: Provides a 30-second preview of the recommended song.
   - **Why Chosen**: Deezer offers a free API for song previews, making it an ideal option for audio playback in the app.

---

## **How to Use the App**

1. **Clone or Download the Project**:
   - Clone the repository or download the project files to your local machine.

2. **Set Up Spotify Developer Account**:
   - Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and log in.
   - Create an app and copy the **Client ID** and **Client Secret**.
   - In the app settings, set the **Redirect URI** (e.g., `http://localhost/callback`).

3. **Set Up Genius API**
  - Go to the [Genius Developer Portal](https://genius.com/developers) and create an app to get your **Genius API Token**.

4. **Set Up Deezer API**:
   - No special setup is needed for Deezer API access as only song previews are used, which are publicly available.

---

## **Instructions to Run the App**

1. **Set Up API Keys**:
   - Replace the placeholder values in the code with your **Spotify Client ID**, **Spotify Client Secret**, and **Genius Token**.

2. **Authorize the App**:
   - When you run the app, a URL will be printed in the console (or optionally opened in the browser).
   - Visit this URL, log in with your Spotify account, and authorize the app.
   - Copy the **authorization code** from the URL and input it into the console when prompted.

3. **View Your Top 5 Songs**:
   - After successfully logging in, the app will display your **top 5 Spotify songs**.

4. **Get a Recommended Song**:
   - The app will fetch a song recommendation based on a pre-defined genre (e.g., **hip-hop**).
   - It will also fetch the **lyrics** for the recommended song using the Genius API.

5. **Listen to the Preview**:
   - The app will provide a **30-second preview** of the recommended song using Deezer, and it will play directly in your browser or terminal.

---
