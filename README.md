# oaqjp-final-project-emb-ai
Final Project

Emotion Detector: a Flask web application that uses the Watson NLP `EmotionPredict`
service to detect anger, disgust, fear, joy and sadness (and the dominant emotion) in a text.

- `EmotionDetection/emotion_detection.py` - the `emotion_detector` function (with status code 400 handling)
- `EmotionDetection/__init__.py` - package definition
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask server, lint score 10/10

```
python3 server.py
python3 -m unittest test_emotion_detection.py
pylint server.py
```
