# SwacchhAI: Live Waste Segregation

Our datasets used to train: https://universe.roboflow.com/ai-project-i3wje/waste-detection-vqkjo/model/3

Colab: https://colab.research.google.com/drive/1dHv5QUuz2NkkgzeKBoO4DLAhLg9mOrzv?usp=sharing

Live: https://intelligent-waste-segregation-system.streamlit.app

Setup

## 🌟 Inspiration

The inspiration for SwacchhAI comes from the critical issue of waste mismanagement in rural areas. People often have little to no awareness about waste segregation, leading to indiscriminate dumping, which contributes to diseases and environmental hazards. SwacchhAI aims to automate and educate through technology.

---

## 🚀 What It Does

SwacchhAI is an AI-based waste segregation system that:

- Uses real-time camera input (no need to upload images).
- Classifies waste into categories: **Recyclable**, **Non-Recyclable**, and **Hazardous**.
- Provides accurate and time-efficient predictions.
- Offers real-time geolocation of detected waste.
- Supports multiple languages for accessibility.
- Includes an **Admin Interface** to:
  - Track users and their data input.
  - Flag and communicate when hazardous waste is detected.

---

## 🛠️ How We Built It

SwacchhAI was developed using a **modular architecture**, including the following components:

1. **Image Upload**: Upload an initial image.
2. **Processing**: A Streamlit/Flask interface processes the image.
3. **View Prediction**: View model predictions with confidence scores.
4. **Live Webcam Feed**: Capture input from webcam.
5. **Real-Time Detection**: Machine Learning model detects objects live.
6. **Waste Classification Logic**: Categorize detected waste.
7. **Prediction Output**: Display categories, accuracy, and labels.

### 🔧 Deployment Stack:

- **Model Framework**: PyTorch
- **Interchange Format**: ONNX
- **Execution**: Edge Computing + Cloud Inference
- **Dual Model Format Support**

---

## 🧗 Challenges We Ran Into

The document does not mention specific challenges.

---

## 🏆 Accomplishments We're Proud Of

- Real-time, accurate waste classification system.
- Helping rural populations with little knowledge of segregation.
- Admin-side tools for safety and communication.
- Applicability in **Smart Bins**, **Factories**, and **Urban Waste Systems**.

---

## 📚 What We Learned

While not explicitly stated, we gained insights into:

- Real-time object detection and classification.
- Modular app design and UI/UX with Streamlit/Flask.
- Multi-platform deployment using ONNX and Docker.
- Integrating Edge + Cloud computing for model inference.

---

## 🔮 What's Next for SwacchhAI

Here are the future plans to elevate SwacchhAI:

- 🎯 **Real-Time FPS Counter**: GPU/CPU-based performance monitor.
- 🗣️ **Feedback System**: Multi-lingual feedback loop to enhance model accuracy.
- 📦 **Dockerized Deployment**: For hosting on Huggingface Spaces and Streamlit Cloud.
- ☁️ **Cloud Integration**: Real-time streaming + data analytics for collaboration.
- 🔥 **Input Heatmaps/Overlays**: Visual insights into model attention and accuracy.
- 🧠 **Advanced Model Output**: Heatmaps, confidence scores, multi-class probability graphs.
- 📊 **Performance Monitoring**: Real-time logs using W&B, system metrics.
- 🔁 **Feedback Loop**: Continual training and improvement via user data.

---

## 📌 Conclusion

SwacchhAI is more than a smart segregation tool—it's a scalable solution with the potential to educate, automate, and revolutionize waste management practices. Through real-time technology, AI, and community-centric features, SwacchhAI aspires to make India—and the world—a cleaner place.

---

References
Streamlit Documentation: https://docs.streamlit.io/

YOLO Documentation: https://github.com/ultralytics/yolov5
