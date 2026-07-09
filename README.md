# Emotion Detection Web Application

An AI-powered web application that analyzes text and identifies the predominant emotion expressed using the IBM Watson NLP Emotion Prediction service. The application is built with Python and Flask and demonstrates how AI can be integrated into a simple web interface for emotion analysis.

## Features

- Detects the following emotions:
  - 😊 Joy
  - 😠 Anger
  - 😢 Sadness
  - 😨 Fear
  - 🤢 Disgust
- Determines the dominant emotion based on the highest confidence score.
- Flask-based web interface.
- Handles blank or invalid input gracefully.
- Includes unit tests for validating application behavior.
- Packaged as a reusable Python module.

## Project Structure

```text
.
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
├── README.md
└── LICENSE
```

## Technologies Used

- Python 3
- Flask
- Requests
- IBM Watson NLP Emotion Prediction API
- unittest
- Pylint

## Installation

Clone the repository:

```bash
git clone https://github.com/adeniranprecious002-ux/oaqjp-final-project-emb-ai.git
```

Navigate to the project directory:

```bash
cd oaqjp-final-project-emb-ai
```

Install the required dependencies:

```bash
pip install flask requests
```

## Running the Application

Start the Flask server:

```bash
python3 server.py
```

Open your browser and navigate to:

```
http://localhost:5000
```

Enter a sentence and click **Analyze Emotion** to view the detected emotions and dominant emotion.

## Example

### Input

```
I think I am having fun.
```

### Output

```
For the given statement, the system response is 'anger': 0.00..., 'disgust': 0.00..., 'fear': 0.00..., 'joy': 0.98... and 'sadness': 0.00.... The dominant emotion is joy.
```

## Running Unit Tests

Run the test suite:

```bash
python3 test_emotion_detection.py
```

## Error Handling

If the user submits a blank input, the application responds with:

```
Invalid text! Please try again!
```

## Code Quality

The project was analyzed using **Pylint** to improve code quality and maintainability.

## Learning Outcomes

This project demonstrates:

- Python package creation
- REST API integration
- JSON parsing
- Flask web development
- Unit testing with `unittest`
- Error handling
- Static code analysis with Pylint
- Git and GitHub workflow

## Author

**Precious Adeniran**

- **GitHub:** https://github.com/adeniranprecious002-ux
- **LinkedIn:** https://www.linkedin.com/in/adeniranprecious/
