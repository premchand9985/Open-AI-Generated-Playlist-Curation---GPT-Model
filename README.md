# AI-Generated Playlist Curation for Spotify

## Overview

This repository hosts an innovative project tailored for Spotify users, utilizing advanced AI technology to craft personalized playlists based on user-provided prompts. Empowered by OpenAI's cutting-edge GPT-3.5 language model, our AI assistant comprehends natural language queries to curate playlists perfectly aligned with your musical preferences.

## Key Features

#### Intelligent Playlist Generation: Our AI assistant comprehends various prompts, including moods, genres, themes, and more, to craft playlists that resonate with your musical taste.
#### Customizable Playlist Length: Specify the desired number of songs for your playlist, and our assistant will curate it accordingly, ensuring a seamless listening experience.
#### Spotify Integration: Seamlessly integrate our provided code snippets with the Spotify API to access your curated playlists directly within the Spotify platform.
#### Flexible and Extensible: The project's codebase is modular and easily customizable, allowing users to tailor the playlist generation functionality to suit their specific needs or integrate it into their own applications.

## Getting Started

Clone the Repository: Begin by cloning this repository to your local machine.
Set Up Spotify API: Obtain API credentials from the Spotify Developer Dashboard and configure your environment variables accordingly.
Install Dependencies: Ensure you have Python installed along with necessary dependencies listed in requirements.txt.
Explore the Code: Dive into the provided Jupyter notebook to understand how our AI assistant generates playlists based on user prompts.
Customize and Extend: Modify the code as needed or integrate the playlist generation functionality into your own Spotify-powered applications.

## Contents
Jupyter notebook: playlist_generator.ipynb
Python scripts:
playlist_generator.py
spotify_playlist.py

## Setup

### 1. Environment Setup:
Make sure you have Python installed on your machine.
Create a virtual environment and activate it.
Install dependencies using pip install -r requirements.txt.

### 2. OpenAI API Key:
Obtain an API key from OpenAI and store it in a .env file in the root directory.

OPENAI_API_KEY=your_openai_api_key

### 3. Spotify API Credentials:

Sign up as a Spotify developer and create an application.
Copy your Client ID and Client Secret to the .env file.

SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret

## Usage

### Jupyter Notebook (playlist_generator.ipynb)
Execute the cells in the notebook to interactively generate playlists based on user prompts.

### Python Scripts
playlist_generator.py
This script provides a command-line interface to generate playlists.
Usage:

python playlist_generator.py -p "your_playlist_prompt" -n number_of_songs

spotify_playlist.py
This script generates a playlist based on a prompt and adds it to the user's Spotify account.
Usage:

python spotify_playlist.py -p "your_playlist_prompt" -n number_of_songs

## Contribute

We welcome contributions from the Spotify community! Whether it involves enhancing the AI model's capabilities, improving documentation, or introducing new features, your contributions are invaluable. Feel free to fork the repository, make your enhancements, and submit a pull request to contribute to our shared musical journey.
