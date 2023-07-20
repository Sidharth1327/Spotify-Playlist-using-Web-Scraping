
# Spotify Billboard Playlist Generator

![billboard](https://github.com/Sidharth1327/Spotify-Playlist-using-Web-Scraping/assets/91174930/8f239275-e269-4664-9628-d36b77163a0f)

## Overview

This project is a Python-based application that generates a personalized Spotify playlist using Billboard's top 100 songs of a specific date. The application utilizes Spotify's API, OAuth authentication, Spotipy (a Python Spotify module), and Beautiful Soup for web scraping to achieve this functionality. By creating a seamless integration between Billboard's top songs and a user's Spotify account, the project offers an interactive and engaging experience for music enthusiasts.

## Features

- OAuth Authentication: Securely authenticates the user's Spotify account to access their playlists.
- Billboard Web Scraping: Utilizes Beautiful Soup to scrape Billboard's website for the top 100 songs on a specific date.
- Playlist Generation: Designs and implements algorithms to create a customized playlist based on the top 100 songs.
- User-Friendly Interface: Provides an intuitive and attractive user interface for ease of use.

## Installation

To run the application, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries: `pip install spotipy beautifulsoup4`.
3. Obtain Spotify API credentials and set them up in the project.
4. Run the application using the command: `python main.py`.

## Usage

1. Launch the application and log in to your Spotify account through OAuth authentication.
2. Select a specific date to generate the playlist from Billboard's top 100 songs of that date.
3. The application will create and populate a new playlist on your Spotify account with the selected songs.

![top 100](https://github.com/Sidharth1327/Spotify-Playlist-using-Web-Scraping/assets/91174930/be2b1ca6-a40d-416f-80b3-857a4004f795)

## Example

```
Welcome to Spotify Billboard Playlist Generator!

Please log in to your Spotify account to get started.

Date (YYYY-MM-DD): 2023-07-01
Creating a playlist based on Billboard's top 100 songs of 2023-07-01...

Playlist "Billboard Top 100 - 2023-07-01" created with 100 songs!

Enjoy your personalized playlist!
```

## Future Enhancements

- Integration with other music charts and platforms to provide more diverse playlist options.
- Implementation of smart playlist creation based on user preferences and music history.
- Addition of playlist sharing features and social media integration.

## Contribution

Contributions to the project are welcome! Feel free to raise issues, suggest improvements, or submit pull requests.


## Credits

Special thanks to Spotify and Billboard for providing access to their APIs and data, and to the Spotipy and Beautiful Soup communities for their invaluable contributions to this project and Dr Angela Yu for giving more insights about the project.

