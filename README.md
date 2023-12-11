# News App

A simple Python application built using Tkinter, requests, and PIL that fetches and displays top headlines from a news API. The application allows users to navigate through news articles, view images, read headlines, and open the full articles in a web browser.

## Features:
- Fetches top headlines from a news API (specifically for India in this case).
- Displays news articles with images, headlines, and descriptions.
- Provides navigation buttons to move between articles (Prev, Next).
- Allows users to read more about an article by opening the link in a web browser.

## Dependencies:
- `requests`: Used for making HTTP requests to the news API.
- `webbrowser`: Enables opening URLs in the default web browser.
- `tkinter`: GUI toolkit for creating the application's graphical user interface.
- `PIL`: Python Imaging Library, used for image processing.

## Usage:
1. Clone the repository.
2. Run the script, and the GUI window will display top news headlines.
3. Navigate through articles using the provided buttons.
4. Click on "Read More" to open the full article in a web browser.

Note: Make sure to replace the API key in the `requests.get` URL with your own key if you plan to use this code beyond a demonstration.

Feel free to customize and enhance the code for your specific use case!
