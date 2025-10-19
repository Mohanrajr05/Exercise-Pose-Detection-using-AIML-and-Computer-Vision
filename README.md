# Exercise Pose Detection & Analysis

![GitHub top language](https://img.shields.io/github/languages/top/Mohanrajr05/Exercise-Pose-Detection-using-AIML-and-Computer-Vision)
![GitHub last commit](https://img.shields.io/github/last-commit/Mohanrajr05/Exercise-Pose-Detection-using-AIML-and-Computer-Vision)
![GitHub repo size](https://img.shields.io/github/repo-size/Mohanrajr05/Exercise-Pose-Detection-using-AIML-and-Computer-Vision)

This project is a web application that uses AI, Computer Vision, and Deep Learning to analyze human poses during exercise. It's built with a **Django** backend and features a **MobileNetV2 + LSTM** model for real-time or video-based action recognition and analysis.

---

## 📋 Table of Contents

-   [About The Project](#about-the-project)
-   [✨ Features](#-features)
-   [🛠️ Tech Stack](#️-tech-stack)
-   [🚀 Getting Started](#-getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installation](#installation)
-   [Usage](#usage)
-   [🤖 Model Training](#-model-training)
-   [📧 Contact](#-contact)

---

## About The Project

The goal of this project is to provide a framework for analyzing exercise movements. It uses a deep learning model to process video input, identify key body landmarks, and classify the actions being performed. The Django web application provides a user-friendly interface to interact with the model.

---

## ✨ Features

-   **AI-Powered Pose Analysis:** Leverages a custom-trained deep learning model for exercise analysis.
-   **Web-Based Interface:** A user-friendly UI built with Django to upload videos or (potentially) use a live webcam feed.
-   **Scalable Backend:** Built on the robust and modular Django framework.
-   **Model Training Pipeline:** Includes a `train_models.py` script to train or fine-tune the `MobileNetV2 + LSTM` model.

---

## 🛠️ Tech Stack

This project combines a full-stack web framework with a deep learning pipeline.

-   **Backend:** **Django**
-   **Deep Learning:** **TensorFlow** / **Keras**
-   **Computer Vision:** **OpenCV**
-   **Model Architecture:** **MobileNetV2** (for spatial feature extraction) + **LSTM** (for temporal sequence analysis)
-   **Language:** **Python**
-   **Frontend:** HTML / CSS / JavaScript (within Django Templates)

---

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

You need Python, pip, and (ideally) a virtual environment manager installed.

-   Python 3.8+
-   pip

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/Mohanrajr05/Exercise-Pose-Detection-using-AIML-and-Computer-Vision.git](https://github.com/Mohanrajr05/Exercise-Pose-Detection-using-AIML-and-Computer-Vision.git)
    cd Exercise-Pose-Detection-using-AIML-and-Computer-Vision
    ```

2.  **Create and activate a virtual environment:**
    ```sh
    # On Windows
    python -m venv venv
    .\venv\Scripts\activate

    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required packages:**
    *(Note: You should create a `requirements.txt` file by running `pip freeze > requirements.txt` in your working environment.)*
    ```sh
    pip install -r requirements.txt
    ```

4.  **Run Django migrations:**
    ```sh
    python manage.py migrate
    ```

5.  **Start the development server:**
    ```sh
    python manage.py runserver
    ```

---

## Usage

Once the server is running, open your web browser and navigate to:

**`http://127.0.0.1:8000/`**

The web interface provided by the `analyzer` app will allow you to upload a video or start a webcam feed for real-time exercise analysis.

---

## 🤖 Model Training

-   To train the model from scratch, you can configure and run the `train_models.py` script.
-   Make sure your dataset is correctly formatted and paths are updated within the script.
-   The trained model files and logs will be saved in the `logs/mobilenetv2_lstm/` directory.

---

## 📧 Contact

Mohan Raj R - [GitHub @Mohanrajr05](https://github.com/Mohanrajr05)
