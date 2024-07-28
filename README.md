# SkyGuard 

SkyGuard is a web application that leverages deep learning to detect drones from video streams. It provides real-time alerts and detailed information about detected drones to ensure security.<br>
Backend code :-[Backend code](https://github.com/AvikshitChanda/SkyGuardBackend)

## Table of Contents 📋

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [File Structure](#file-structure)
- [License](#license)
- [Contributing](#contributing)

## Overview 🌟

SkyGuard is designed to provide real-time monitoring and detection of unauthorized drone activities. It uses a pre-trained deep learning model to analyze video streams and identify the presence of drones, alerting users with visual and auditory notifications.

## Features ✨

- 📹 Real-time video stream analysis
- 🔍 Automatic drone detection
- 🔔 Audio and visual alerts upon detection
- 📜 Detailed messages of detected drones
- 🌐 Responsive web interface

## Installation 🛠️

### Prerequisites

- Node.js
- npm
- React Js
- TensorFlow
- OpenCV
- Pillow
- NumPy
- joblib

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/SkyGuard.git
    cd SkyGuard
    ```

2. Install the required packages for the frontend:

    ```bash
    npm install
    ```

3. Install the required packages for the backend:

    ```bash
    pip install -r requirements.txt
    ```

4. Download and place the models (`model2.h5` and `MobileNet_Transfer_Learning_ANN.joblib`) in the project directory.

## Usage 🚀

1. Start the React frontend:

    ```bash
    npm start
    ```

2. Run the Streamlit backend:

    ```bash
    streamlit run app.py
    ```

3. Open your browser and navigate to `http://localhost:3000` for the frontend and `http://localhost:8501` for the backend.

## Technologies 🧪

- **Frontend:** React, Streamlit
- **Backend:** TensorFlow, OpenCV, NumPy, Pillow
- **Models:** Pre-trained CNN model and an ANN model for drone detection

## File Structure 📁

```plaintext
SkyGuard/
│
├── public/                  # Public assets
│   ├── index.html
│   └── ...
├── src/                     # React frontend source code
│   ├── Assets/              # Assets like images and videos
│   ├── Components/          # React components
│   ├── Pages/               # React pages
│   ├── App.js               # Main React component
│   └── index.js             # Entry point for React
├── backend/                 # Backend source code
│   ├── app.py               # Main application script
│   └── ...
├── models/                  # Pre-trained models
│   ├── model2.h5
│   └── MobileNet_Transfer_Learning_ANN.joblib
├── requirements.txt         # Python package dependencies
├── package.json             # npm package dependencies
├── README.md                # Readme file
└── ...
