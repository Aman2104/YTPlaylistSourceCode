# YouTube Playlist Length Calculator

This repository contains the source code for a YouTube Playlist Length Calculator website. You can see a live demo of this application [here](https://ytplaylist-length.netlify.app/).

## How to Run the Application

To work on this application locally, follow these steps:

1. Clone this repository to your local machine.

   ```shell
   git clone https://github.com/Aman2104/YTPlaylistSourceCode.git



2. To use this YouTube Playlist Length Calculator, you need to set up your YouTube API Key. Follow the steps below:

## Create a YouTube API Key

1. Visit the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing one.
3. Enable the "YouTube Data API v3" for your project.
4. Create an API Key.

## Replace the API Key in the Code

After obtaining your API Key, replace `"API KEY"` in the `index.js` file with your actual API Key from the Google Cloud Console.

## Running the Application

You can run the application locally or deploy it to a web hosting service:

1. Open the `index.html` file in a web browser to run it locally.
2. Alternatively, deploy the application to a web hosting service of your choice.

## How the Application Works

This web application allows you to calculate the total length of a YouTube playlist and provides the total time for various playback speeds (1x, 1.25x, 1.5x, 1.75x, 2x). You can input the playlist URL, specify the range of videos you want to calculate, and then click the "Calculate" button to see the results.

## Dependencies

This project uses the following technologies and libraries:

- JavaScript
- HTML/CSS
- [YouTube Data API v3](https://developers.google.com/youtube/registering_an_application)