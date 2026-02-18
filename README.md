#  Facial Emotion Recognition using PyTorch

This project implements a **Deep Learning Classifier** to recognize facial expressions and emotions from images. The system is built using **PyTorch** and follows a robust pipeline for data handling, augmentation, and model training.

---

##  Key Features
* **Automated Data Acquisition:** Integrated with **Kagglehub** to automatically fetch the latest version of the Emotion Recognition Dataset.
* **Multi-Class Classification:** Capable of identifying 6 distinct facial expressions: *Ahegao, Angry, Happy, Neutral, Sad, and Surprise*.
* **Data Augmentation:** Implements `transforms` including Random Rotation and Color Jitter to improve model generalization.
* **Custom Dataset Architecture:** Features a tailored PyTorch `Dataset` class to handle image loading and on-the-fly preprocessing.

---

##  Tech Stack
* **Framework:** PyTorch
* **Data Handling:** Pandas, Scikit-learn (Train-Test Split).
* **Image Processing:** PIL (Pillow), Torchvision Transforms.
* **Environment:** Designed for Google Colab/Jupyter with Kaggle API integration.

---

##  How to Use

### 1. Prerequisites
Install the necessary libraries for dataset downloading and image processing:
```bash
pip install torch torchvision pandas pillow kagglehub scikit-learn
```

### 2. Dataset Setup
* The project uses the `sujaykapadnis/emotion-recognition-dataset` from Kaggle.
* The script automatically downloads and organizes image paths using the `kagglehub` library.
* Data is split into **80% Training** and **20% Testing** sets to ensure reliable evaluation.

### 3. Training Workflow
* **Load Data**: The `kagglehub` library handles the automated dataset download and path management.
* **Preprocessing**: Images are resized to **224x224** pixels and normalized to match standard neural network input requirements.
* **Training**: Execute the training cells to fit the model on the processed facial expression data.

---

### Author

- **Salem Zain Alaidaroos**
- Computer Science Student
- AI and Software Engineering Enthusiast
