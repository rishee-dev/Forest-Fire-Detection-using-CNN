<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN-orange?style=for-the-badge&labelColor=111111">
  <img src="https://img.shields.io/badge/TensorFlow-Keras-FF6F00?style=for-the-badge&labelColor=000000">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&labelColor=000000">
  <img src="https://img.shields.io/badge/AICTE-Skills4Future-green?style=for-the-badge&labelColor=000000">
  <img src="https://img.shields.io/badge/license-MIT-444444?style=for-the-badge&labelColor=000000">
</p>

<h1 align="center">🔥 Forest Fire Detection using CNN</h1>

<p align="center">
An AI-powered computer vision system that detects <b>forest fires from images</b> using a Convolutional Neural Network (CNN) for early wildfire detection and disaster prevention.
</p>

<p align="center">
🌲 Computer Vision • 🤖 Deep Learning • 🔥 Wildfire Detection
</p>

---

# 🧠 Overview

This project was developed during the **AICTE–Shell–Edunet Foundation Skills4Future Internship**.

The objective is to build a **Convolutional Neural Network (CNN)** capable of classifying images into **Fire** and **No Fire** categories by learning visual features such as flames, smoke, and fire patterns.

The model can assist in **early wildfire detection**, enabling faster emergency response and reducing environmental damage.

---

# ⚡ Features

| Feature | Description |
|----------|-------------|
| 🔥 Fire Detection | Detects forest fires from images |
| 🧠 CNN Model | Deep learning-based image classification |
| 📷 Image Classification | Predicts Fire / No Fire |
| ⚡ GPU Training | TensorFlow GPU acceleration supported |
| 📊 Model Evaluation | Accuracy & validation metrics |
| 🌲 Wildfire Dataset | Trained using a labeled wildfire dataset |

---

# 🏗 Project Architecture

```text
Forest Fire Images
        │
        ▼
Image Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
Convolutional Neural Network
        │
        ▼
Feature Extraction
        │
        ▼
Dense Layers
        │
        ▼
Prediction
        │
 ┌──────────────┐
 │ Fire         │
 │ No Fire      │
 └──────────────┘
```

---

# 📂 Dataset

The model is trained using the **Wildfire Dataset** containing two classes:

- 🔥 Fire
- 🌲 No Fire

The dataset is automatically downloaded from Kaggle using **kagglehub**.

---

# 📦 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- KaggleHub

---

# ⚙️ Model Workflow

### 1️⃣ Download Dataset

The wildfire dataset is downloaded directly from Kaggle.

### 2️⃣ Data Preprocessing

- Resize images
- Normalize pixel values
- Data augmentation
- Train / Validation / Test split

### 3️⃣ Model Training

A CNN is trained to learn distinguishing features between forest fire and non-fire images.

### 4️⃣ Prediction

The trained model classifies unseen images into:

- 🔥 Fire
- 🌲 No Fire

---

# 🧠 CNN Architecture

```
Input Image
      │
      ▼
Conv2D
      │
MaxPooling
      │
Conv2D
      │
MaxPooling
      │
Flatten
      │
Dense Layer
      │
Dropout
      │
Output Layer
      ▼
Fire / No Fire
```

---

# 📈 Results

The trained CNN successfully learns visual patterns associated with wildfire images and predicts whether an image contains a forest fire.

The model can be extended for deployment in:

- Drone surveillance
- Satellite imagery
- CCTV monitoring
- Smart forest monitoring systems
- IoT-based wildfire alert systems

---

# 🛠 Installation

### Clone Repository

```bash
git clone https://github.com/rishee01/forest-fire-detection-cnn.git
```

### Move into Project

```bash
cd forest-fire-detection-cnn
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run

Launch the Jupyter Notebook:

```bash
jupyter notebook
```

or

```bash
python forest_fire_detection.py
```

---

# 📊 Future Improvements

Planned enhancements include:

- 🎥 Real-time webcam fire detection
- 🚁 Drone-based forest monitoring
- ☁️ Cloud deployment
- 📱 Mobile application
- 🌍 Satellite image analysis
- 📡 IoT sensor integration
- 🚨 Automatic emergency alert system

---

# 📚 Internship Information

**Program**

AICTE – Shell – Edunet Foundation

**Internship**

Skills4Future AI & Green Technology Internship

**Project**

Forest Fire Detection using Convolutional Neural Networks (CNN)

---

# 📊 GitHub Stats

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rishee01&show_icons=true&theme=tokyonight">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rishee01&theme=tokyonight">

</p>

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Maharishee Ambati**

Exploring:

- 🤖 Artificial Intelligence
- 🧠 Deep Learning
- 👁️ Computer Vision
- ☁️ Cloud Computing

---

<p align="center">

⭐ If you found this project useful, consider giving it a star!

</p>
