# Emotion Detection with Watson NLP

A Flask web application that detects the emotions (anger, disgust, fear,
joy, sadness) expressed in a piece of text, using IBM Watson NLP's
emotion prediction service, and reports the dominant emotion.

## Files
- `EmotionDetection/emotion_detection.py` — core emotion detection logic
- `EmotionDetection/__init__.py` — package initializer
- `server.py` — Flask web server
- `templates/index.html`, `static/mywebscript.js` — front end
- `test_emotion_detection.py` — unit tests

## Run
```
pip install -r requirements.txt
python server.py
```
