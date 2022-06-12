# Spotify Brazilian Rap data analysis a.k.a. Pique

Brazilian rap data analysis with Spotify data, collected via API.

Qual a cena do rap?

## Data collection
### api_caller.py

`api_caller.py` calls Spotify API.

It needs:
- export client ID on local terminal: SPOTIPY_CLIENT_ID and SPOTIPY_CLIENT_SECRET
    - collected via [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications)
    - Spotipy docs: [link](https://spotipy.readthedocs.io/en/2.9.0/)
    
- needs to aggregate musics outside major playlists as well
    
## Preprocessing
### preprocessing.ipynb

Dataset date is fixed by the last data collection time.

Needs to:
- remove duplicates by name


## Data analysis
### analysis.ipynb
WIP

## Inference
### inference.ipynb
WIP