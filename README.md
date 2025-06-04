# Moodify: Playlist Generator Based on User Mood

Moodify is a conversational Jupyter notebook assistant that classifies your mood, fetches a relevant Spotify playlist, and responds with a witty, mood-aware remark.

## Features

- Classifies natural language mood input into predefined categories.
- Maps moods to curated Spotify search terms.
- Fetches a relevant playlist using Spotify's API.
- Closes the loop with a humorous comment using GPT-4o.

## Setup Instructions

1. Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/shreya-lakshman/moodify.git
cd moodify
``` 

2, **Install Requirements**

```bash
pip install -r requirements.txt
```

3. **Add a `.env` File**

```dotenv
OPENAI_API_KEY=your_openai_key
SPOTIFY_CLIENT_ID=your_client_id
SPOTIFY_CLIENT_SECRET=your_client_secret
```
**Proceed to source the .env file using commandline**

```bash
source .env
```

4. **Launch Jupyter and Run the Notebook**

```bash
jupyter notebook
# Open Moodify.ipynb
```

## Requirements

- Python 3.8+
- OpenAI API Key
- Spotify Developer Credentials

## Notes

- You must have a valid Spotify Developer account to generate API credentials. Visit https://developer.spotify.com/dashboard to create a project and obtain your Client ID and Secret.
- OpenAI access requires a valid API key from https://platform.openai.com/account/api-keys.

