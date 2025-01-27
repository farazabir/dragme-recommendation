# dragme-recommendation
A content-based recommendation system for events using TF-IDF vectorization and approximate nearest neighbors search with Annoy.

## Features

- Fetches event data from Dragme.io API
- Preprocesses and combines text features (event name, location city, event info)
- TF-IDF vectorization for text processing
- Annoy index for efficient similarity search
- Event recommendation function based on event ID
- Visualization of top event locations

## Prerequisites
- Python 3.x
- API access token for Dragme.io
