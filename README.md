# 🎬 Mood Recognition Movie Recommender

## Overview
This Python project is a mood-based movie recommendation system. Users input their current mood, and the system fetches movie suggestions based on that emotion using the OMDb API.

## Features
- Detects user mood through text input
- Maps moods to genre-based keywords
- Fetches movie data using OMDb API
- Displays top 5 movies per keyword
- Interactive looping for additional suggestions

## Technologies Used
- **Python**
- **OMDb API** (https://www.omdbapi.com)
- `requests` module for API interaction
- `random` for selecting keywords
- `input()` and `print()` for CLI interaction

## Moods Supported
- Happy 😊
- Sad 😢
- Excited 😃
- Romantic ❤️
- Scared 😱
- Relaxed 😌
- Adventurous 🧭

## How It Works
1. User inputs their current mood.
2. Mood is mapped to keywords (e.g., "happy" → "comedy", "animated").
3. A keyword is selected at random.
4. OMDb API is called with the keyword to fetch matching movies.
5. Top 5 results are displayed with titles and release years.

## Future Enhancements
- Detect mood from text or facial expressions using AI.
- Display movie posters, ratings, and summaries.
- Build a user-friendly web or mobile interface.
- Add support for more moods, languages, and preferences.

MADEBY:
SMIT TIMBADIYA
YASH JADAV
VISWARAJ SOLANKI
RAJ ODHA
