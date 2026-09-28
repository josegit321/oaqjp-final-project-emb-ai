# Emotion Detector

An AI-based web application that detects the emotions (anger, disgust, fear, joy and sadness) in a text and reports the dominant emotion, using the Watson NLP EmotionPredict service.

## Project structure

- `EmotionDetection/` - package with the `emotion_detector` function
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask web deployment
- `templates/`, `static/` - web interface

## Run

    python3.11 -m pip install flask requests
    python3.11 server.py
