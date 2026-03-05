# oaqjp-final-project-emb-ai

## Emotion Detection Application

This project is the final project for the **Developing AI Applications with Python and Flask** course. It builds an AI-based web application using the Watson NLP Emotion Detection library.

## Project Structure

```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Features

- Detects emotions (anger, disgust, fear, joy, sadness) from text input
- Returns the dominant emotion
- Error handling for blank/invalid input
- Flask web deployment
- Unit tested with Python unittest
- Static code analysis with pylint (10/10)

## How to Run

```bash
pip install flask requests
python server.py
```

Then open `http://localhost:5000` in your browser.

## Run Tests

```bash
python -m pytest test_emotion_detection.py -v
```

## Static Code Analysis

```bash
pylint server.py
```
