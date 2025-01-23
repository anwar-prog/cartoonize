# Cartoon Maker

A Python-based application that converts images and videos into cartoon-style visuals using a combination of **Machine Learning** and **image processing techniques**. This project is built with **Flask**, **OpenCV**, and **TensorFlow** and includes Google Cloud integration for handling storage and APIs.

---

## 🎯 Features
- Upload and cartoonize images in real-time.
- Upload videos for cartoonized processing.
- Save and download processed images and videos.
- Configurable settings for local or cloud-based operation.
- Docker support for easy deployment.

---

## 🛠️ Technology Stack
- **Backend:** Flask
- **Image Processing:** OpenCV
- **Machine Learning:** TensorFlow, White-Box Cartoonizer
- **Video Handling:** scikit-video
- **Cloud Storage:** Google Cloud Storage
- **Containerization:** Docker

---

## 🚀 Installation and Setup

### Prerequisites
1. Python 3.6 or later installed on your system.
2. A Google Cloud account for cloud storage (optional).
3. Docker (optional for containerized deployment).

. ├── app.py # Main Flask application ├── gcloud_utils.py # Google Cloud Storage utilities ├── video_api.py # API integration for video processing ├── templates/ # HTML templates for the web interface ├── static/ # Static assets (e.g., images, videos, JS) │ ├── cartoonized_images/ │ ├── sample_images/ │ ├── uploaded_videos/ │ └── upload.js ├── white_box_cartoonizer/ # Pre-trained model and scripts ├── config.yaml # Application configuration ├── Dockerfile # Docker configuration ├── requirements.txt # Python dependencies ├── LICENSE # License information ├── README.md # Project documentation └── .gitignore # Git ignore rules

### 🌐 Demo
Upload an image or video via the web interface.
The cartoonized result will be processed and made available for download.


### Clone the Repository
```bash
git clone https://github.com/anwar-prog/cartoonize.git
cd cartoonize

