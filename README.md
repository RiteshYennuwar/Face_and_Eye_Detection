# Flask Video Streaming with OpenCV

This project implements a simple live video streaming application using Flask and OpenCV.

## Overview

The application sets up a Flask server to handle video stream requests and uses OpenCV to capture and process video frames. The live video stream is displayed on a web page.

## Preview
<img src="static/images/preview.png" alt="app preview">

## Project Structure

- `app.py`: The main Flask application file that handles video streaming.
- `templates/index.html`: The HTML template that displays the live video stream.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/RiteshYennuwar/Video_Streaming
    cd Video_Streaming
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:
    ```bash
    python app.py
    ```

2. Open your web browser and go to http://127.0.0.1:5000 to see the live video stream.
