# Object Detection with Python, Flask, and YOLOv8

This project demonstrates a simple web application for object detection using Python, Flask, and YOLOv8. The application can detect objects in video streams as well as uploaded images.

## Features

- **Video Stream Detection**: Detect objects in a live video stream at the '/' route.
- **Image Upload Detection**: Upload images for object detection at the '/test_upload' route.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.11
- Flask
- OpenCV
- YOLOv8

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1. **Start the Flask Server**:
    ```bash
    flask run
    ```

2. **Access the Application**:
    - Video Stream Detection: Open your browser and navigate to `http://127.0.0.1:5000/`
    - Image Upload Detection: Open your browser and navigate to `http://127.0.0.1:5000/test_upload`

## Usage

### Video Stream Detection

Navigate to the '/' route to start the video stream and see real-time object detection.

### Image Upload Detection

Navigate to the '/test_upload' route to upload an image and see the detected objects.

## Project Structure
  ├── app.py # Main Flask application
  ├── requirements.txt # Python dependencies
  ├── static/ # Static files (e.g., CSS, JavaScript)
  ├── templates/ # HTML templates
  └── README.md # Project documentation




![Screenshot 2024-06-03 at 12 46 48](https://github.com/Warszawa1/object_detection/assets/48474962/48b60b04-fa3d-4f43-859b-409df4d6a66e)
![Screenshot 2024-06-03 at 13 30 48](https://github.com/Warszawa1/object_detection/assets/48474962/7ea6d91c-6a90-4601-9acf-95f9d08225ce)
![Screenshot 2024-06-03 at 12 46 20](https://github.com/Warszawa1/object_detection/assets/48474962/ebea5f03-e074-4b87-8172-7a467b971e6d)



