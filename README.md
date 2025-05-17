# 🐾 Cat vs Lion Image Classifier

This is a simple image classification project built with a model trained using [Teachable Machine](https://teachablemachine.withgoogle.com/).  
It classifies uploaded images into two categories: **Cat** or **Lion**.

## 🚀 How it works

1. A model was trained using Teachable Machine with two classes: Cat and Lion.
2. The model was exported in TensorFlow format and converted for use with Keras.
3. A Python script (`classify.py`) allows the user to input an image, and the model returns the predicted class.

## 🧠 Model Info

- Input size: 224x224 pixels
- Model format: `.h5` (converted from TensorFlow.js)
- Labels:  
  - `CAT`  
  - `LION`

## 📦 Files

- `converted_model/model.h5`: The trained and converted model.
- `labels.txt`: Class labels in order.
- `classify.py`: Python script to test the model with an image.
- `test.jpg`: Sample image (optional).

## 🛠 How to Use

1. Install required libraries:
    ```bash
    pip install tensorflow pillow numpy
    ```

2. Run the classifier script:
    ```bash
    python classify.py
    ```

3. Enter the path to your image when prompted.

## ✅ Example Output

![screenshot](لقطة%20شاشة%202025-05-17%20170515.png)

