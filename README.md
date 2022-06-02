# play-with-spotipy

A sandbox script with the `spotipy` Python library.

## Requirements

Python 3.10  
`ipykernel` (to work in notebooks)
`python-dotenv` (to manage [Spotify credentials](#spotify-credentials))
`spotipy` (to make requests to the Spotify API)

Create a new virtual environement and install the requirements:
`pip install -r requirements.txt`

## Spotify credentials

Create a Spotify development application [here](https://developer.spotify.com/dashboard/applications).  
Then create a `.env` file in the project folder with:
- `SPOTIFY_CLIENT_ID=your-client-id`
- `SPOTIFY_CLIENT_SECRET=your-client-secret`

## Usage

Open the `script.ipynb` notebook either in VSCode or with `jupyter notebook` and run it.
