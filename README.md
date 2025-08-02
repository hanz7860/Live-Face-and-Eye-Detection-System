# Live Face and Eye Detection System

A web-based application built with **Flask** and **OpenCV** that performs real-time face and eye detection using your webcam or uploaded images.

## 🌟 Features

- 🔴 **Live Detection**: Detects faces and eyes in real-time using your device’s webcam.
- 🖼️ **Image Upload Detection**: Upload any image and receive a processed image with faces and eyes marked.
- 📊 **Face Count Overlay**: Displays the number of detected faces on the video/image.
- 📦 Cleanly structured Flask web app using OpenCV’s Haarcascade classifiers.

## 🛠️ Technologies Used

- Python 3
- Flask
- OpenCV
- HTML/CSS (Jinja2 templating)
- Bootstrap (optional enhancement)

## 📁 Project Structure

Live-Face-and-Eye-Detection-System/
│
├── app.py # Main Flask application
├── main.py # Template PyCharm script (not used in app)
├── templates/
│ └── index.html # Main web interface
├── static/
│ └── uploads/ # Stores uploaded and processed images
├── haarcascades/
│ ├── haarcascade_frontalface_default.xml
│ └── haarcascade_eye.xml
└── README.md


## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Live-Face-and-Eye-Detection-System.git
cd Live-Face-and-Eye-Detection-System

2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

Note: If requirements.txt doesn't exist, manually install:
pip install flask opencv-python

4. Ensure Haarcascade files are in place
Place the following in a haarcascades/ folder:

haarcascade_frontalface_default.xml

haarcascade_eye.xml

5. Run the app
python app.py

Then, go to http://127.0.0.1:5000/ in your browser.
