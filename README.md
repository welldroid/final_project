# Final Project - Emotion Detection Application

## Project Description
This project is an AI-based web application that performs emotion detection 
on text input using IBM Watson NLP. The application analyzes text and returns 
the emotions detected, including anger, disgust, fear, joy, and sadness, 
along with the dominant emotion.

## Features
- Emotion detection using IBM Watson NLP
- Web deployment using Flask
- Error handling for blank entries
- Unit testing with PyLint static code analysis

## Technologies Used
- Python 3
- Flask
- IBM Watson NLP
- PyLint
- Unittest

## How to Run
1. Clone the repository
2. Install dependencies:
```
   pip install flask requests
```
3. Run the server:
```
   python3 server.py
```
4. Access the application at `http://localhost:5000`

## Project Structure
```
oaqjp-final-project-emb-ai/
├── server.py
├── test_emotion_detection.py
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
└── static/
    └── mywebscript.js
```
