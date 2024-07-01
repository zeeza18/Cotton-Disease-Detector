# Cotton Disease Detector

The Cotton Disease Detector is a machine learning-based application that helps detect diseases in cotton plants through image analysis. This project is built using Python and Flask.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction
The Cotton Disease Detector leverages convolutional neural networks (CNNs) to classify and identify diseases in cotton plant leaves. This tool is designed to assist farmers and agricultural professionals in early disease detection and management.

## Features
- Image upload and disease detection.
- User-friendly web interface.
- Accurate and fast disease classification.

## Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.7 or later
- pip (Python package installer)

## Installation
Follow these steps to set up the project on your local machine.

1. **Clone the repository:**
    ```bash
    git clone https://github.com/zeeza18/Cotton-Disease-Detector.git
    cd Cotton-Disease-Detector
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application
1. **Set the Flask app environment variable:**
    ```bash
    export FLASK_APP=app.py
    ```

2. **Run the Flask application:**
    ```bash
    flask run
    ```

    By default, the application will run on `http://127.0.0.1:5000/`.

## Usage
1. **Open your web browser and navigate to the application:**
    ```
    http://127.0.0.1:5000/
    ```

2. **Upload an image of a cotton plant leaf:**
    - Click on the 'Choose File' button to select an image from your local machine.
    - Click 'Submit' to upload the image for analysis.

3. **View the results:**
    - The application will process the image and display the detected disease (if any).

## Acknowledgements
Special thanks to Krish Naik for his tutorials and guidance in building machine learning projects.

## License
MIT License

