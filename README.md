# Emotion Prediction using Deep Learning

This project is designed to predict human emotions based on real-time data, leveraging deep learning techniques. The model detects emotions from video streams (likely from webcam input) and outputs predictions based on the trained deep learning model.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Description](#model-description)
- [Results](#results)
- [Theoretical Questions](#theoretical-questions)

---

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/George-glor/EmotionPrediction_deepLearning.git
   ```

2. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Ensure that you have access to a webcam** for live emotion detection.

---

## Usage

1. To start the webcam and begin emotion prediction, run the following script:

   ```bash
   python StartTheWebcameForgussing.py
   ```

2. The model will process the video feed and display real-time predictions of emotions.

---

## Project Structure

- **StartTheWebcameForgussing.py**: Script to start the webcam for capturing video and running the emotion detection model.
- **emotion detection model.ipynb**: Jupyter notebook containing the implementation of the deep learning model.
- **emotion_detection_model.h5 / emotion_detection_model.keras**: Pre-trained deep learning models.
- **test_loss_test_accuracy.ipynb**: Jupyter notebook to evaluate the model's accuracy and loss on the test data.
- **Teoretiska Frågor.pdf**: Document with theoretical questions or explanations related to the project.

---

## Model Description

The emotion detection model is a convolutional neural network (CNN) designed to classify human emotions from facial expressions in video frames. The model has been trained on a dataset of facial expressions, and its weights are saved in the `emotion_detection_model.h5` file.

**Key features of the model**:
- **Input**: Frames captured from the webcam.
- **Output**: Prediction of emotions (e.g., happy, sad, angry, surprised, etc.).

---

## Results

The model's performance is evaluated using standard metrics such as accuracy and loss, which can be found in the `test_loss_test_accuracy.ipynb` notebook. Results may vary based on the quality of the input video feed and lighting conditions.

---

## Theoretical Questions

The file `Teoretiska Frågor.pdf` contains theoretical questions and discussions that provide insight into the methodology used in this project.
