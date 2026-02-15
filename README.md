# Emotion-Detection
This project is a Flask-based web application that performs emotion analysis on textual input using an external Natural Language Processing (NLP) API.
The backend server processes user-submitted text, sends a request to an emotion analysis API, extracts emotion scores from the response, and determines the dominant emotion. The results are returned in JSON format and displayed dynamically on the frontend.

Features
1. Accepts user text input via a web interface
2. Sends HTTP request to external emotion analysis API
  Extracts:
    1. Emotion scores (e.g., joy, anger, sadness, etc.)
    2. Most dominant emotion
    3. Returns structured JSON response
    4. Displays results dynamically using JavaScript
