# Hand Gesture Recognition using Teachable Machine

This project uses a trained model from Google's [Teachable Machine](https://teachablemachine.withgoogle.com/) to recognize **hand gestures** in real time using a webcam and classify them into four categories:

- **Fist**
- **Palm**
- **Like (Thumbs up)**
- **Peace**

---

## 🔍 Overview

The goal of this project is to demonstrate how hand gesture recognition can be implemented using machine learning models trained on Teachable Machine, and deployed with Python using OpenCV and Keras.

This system captures the webcam feed, classifies the current hand gesture, and outputs the predicted label with a confidence score.

---

## 🎯 Use Cases

This model can be used in different environments and for various applications, such as:

- Interfaces for controlling devices using gestures instead of physical buttons
- Smart home systems (e.g., turn off/on lights using a specific gesture)
- Educational tools for kids to interact using hand signals
- Human-computer interaction where physical input is not practical

---

## 🧠 Model Training

The model was trained on Teachable Machine using images categorized into four labels:

- `fist`
- `palm`
- `like`
- `peace`

Images were sourced from [Kaggle](https://www.kaggle.com/) and curated to include multiple hand types, colors, and angles to enhance generalization.

---

## 🖥️ Demo

A short video demonstration is available in the `assets/` folder showing the model in action.

---

## 📂 Project Structure

```bash
hand-gesture-project/
├── keras_model.h5
├── labels.txt
├── gesture_cam.py
├── LICENSE.txt
├── README.md
├── assets/
│   ├── demo.mp4
│   ├── sample_fist.png
│   ├── sample_palm.png
│   └── ...
```

---

## 📌 How to Run

1. Clone the repository
2. Make sure you have Python 3.10+ and dependencies installed
3. Run the script:

```bash
python gesture_cam.py
```

Make sure the webcam is connected and accessible.

---

## 📃 License

This project is licensed under the MIT License - see the [LICENSE.txt](./LICENSE.txt) file for details.

---

## 👤 Author

Fatima Fahad\
[LinkedIn](https://www.linkedin.com/in/fatima-fahad2)\
[GitHub Profile](https://github.com/quifA)

