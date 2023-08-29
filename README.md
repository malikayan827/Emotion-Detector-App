# Emotion-Detector-App
Project Title: Emotion Detection Web Application

Description:
The Emotion Detection Web Application is a Python-based project that leverages IBM Watson's Natural Language Processing (NLP) capabilities to analyze and predict emotions from text input provided by users. The application provides a user-friendly interface where users can enter text statements, and the system uses the Watson NLP library to determine the emotions associated with the input. The project involves the creation of a Flask-based web application that serves as an interface to interact with the Watson NLP service.

Key Features:

Emotion Analysis: The core functionality of the application is to analyze the emotions expressed in the text input. The application uses the Emotion Predict function of the Watson NLP library to provide insights into emotions like anger, disgust, fear, joy, and sadness.

User-Friendly Interface: The project includes a user interface that allows users to input text statements. The application then processes the input and displays the emotions detected, along with the dominant emotion.

Error Handling: The application incorporates error handling to manage blank entries. If a user submits an empty input, the system provides an error message indicating that the text input is invalid and prompts the user to try again.

Display of Results: The application displays the detected emotions along with their respective scores and identifies the dominant emotion. The results are presented in a user-friendly format, enhancing user understanding.

Web Deployment: The project utilizes the Flask framework to create a web server that hosts the emotion detection application. The application is deployed locally on localhost:5000, enabling users to access and use the tool through a web browser.

Static Code Analysis: The project ensures code quality by conducting static code analysis using tools like PyLint. This helps maintain clean and well-structured code.

Testing: The application is thoroughly tested for various input scenarios, including both valid and blank inputs, to ensure that the error handling and emotion detection functionalities work as intended.

The Emotion Detection Web Application showcases the integration of IBM Watson's NLP capabilities with a user-friendly web interface. The project's key focus on error handling, result presentation, and code quality makes it a practical tool for anyone interested in exploring the emotions expressed in text. Whether for personal use or as a starting point for more advanced emotion analysis applications, this project provides valuable insights into the realm of natural language processing and sentiment analysis.
