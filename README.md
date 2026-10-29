# Final Project - Emotion Detection Application

A web-based emotion detection application developed using Python, Flask, and the Watson NLP Emotion Predict library. The application evaluates emotion metrics (anger, disgust, fear, joy, and sadness) from textual input and identifies the dominant emotion.

## Author
Harsh Manjramkar

## Features
- Real-time emotion detection for given text statements
- Analysis of 5 emotions: anger, disgust, fear, joy, and sadness
- Dominant emotion identification
- Robust error handling for invalid or blank inputs (HTTP 400)
- RESTful web interface deployed using Flask
- Static code analysis adhering to PEP 8 standards with a 10.00/10 rating

## Project Structure
```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── 6b_deployment_test.png
├── 7c_error_handling_interface.png
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/HarshManjramkar/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   ```
2. Install dependencies:
   ```bash
   pip install requests flask pylint
   ```
3. Run unit tests:
   ```bash
   python3 test_emotion_detection.py
   ```
4. Run static code analysis:
   ```bash
   pylint server.py
   ```
5. Start the Flask application:
   ```bash
   python3 server.py
   ```
6. Access the web interface at `http://localhost:5000`.
