# Farmbot
# 🌱 ML-Based IoT FarmBot — Smart Farming Robot

> An IoT-enabled farming robot that uses machine learning and computer vision to monitor crops, detect plant disease, and support smarter, more sustainable agriculture.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/Deep%20Learning-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-ThingSpeak-009999?style=flat)


---

<!-- 📸 ADD PHOTO HERE — main/hero photo of your FarmBot. Replace the line below: -->
![Prototype](Farmbot (others files)/Farmbotfinal.jpg)

## 📖 Overview

The **ML-Based IoT FarmBot** is a smart-farming robot developed as my undergraduate thesis. It combines environmental sensing, IoT cloud connectivity, and a deep-learning model for **plant-disease detection** to help growers monitor crop health and respond early — reducing losses and supporting sustainable farming.

> `[Add 1–2 sentences on your specific motivation — e.g. the crop you targeted (tomato?), the problem in local agriculture you wanted to solve.]`

## 📸 Demo & Gallery

<!-- 📸 ADD PHOTO HERE — a few photos: the build, it working in the field, the dashboard/app -->
| | |
|---|---|
| ![Build](images/build.jpg) | ![In field](images/field.jpg) |
| *Hardware build* | *Operating in the field* |

## ✨ Features

- 🌡️ Real-time environmental monitoring — `[soil moisture, temperature, humidity — list your sensors]`
- 🧠 Deep-learning **plant-disease detection** from leaf images
- ☁️ IoT data logging and remote monitoring via **ThingSpeak**
- 📲 Automatic alerts/notifications — `[e.g. Twilio SMS, if used]`
- 🤖 `[Autonomous / remote-controlled movement — if your bot is mobile]`
- 💧 `[Automated watering / actuation — if applicable]`

## 🧩 System Architecture

<!-- 📸 ADD PHOTO HERE — your block/architecture or wiring diagram (export from Fritzing/Proteus) -->
![System architecture](images/architecture.png)

**Data flow:** sensors & camera → microcontroller → ThingSpeak (cloud) → ML model → disease diagnosis & alerts.

## 🛠️ Hardware Components

| Component | Purpose |
|---|---|
| `[Microcontroller — e.g. Arduino Uno / ESP32]` | Main controller |
| `[Camera module]` | Capturing leaf images for disease detection |
| `[Soil moisture sensor]` | Soil condition monitoring |
| `[DHT11 / DHT22]` | Temperature & humidity |
| `[Motors + driver / wheels]` | Mobility *(if applicable)* |
| `[Water pump / relay]` | Automated watering *(if applicable)* |

## 🧠 Machine Learning

- **Task:** plant-disease classification from leaf images
- **Approach:** `[CNN / transfer learning — name the architecture if you used one]`
- **Dataset:** `[e.g. PlantVillage]`, with **synthetic data augmentation**
- **Frameworks:** `[TensorFlow / PyTorch]`, trained in Google Colab
- **Performance:** `[add your accuracy / key metrics]`

<!-- 📸 ADD PHOTO HERE — training curves, confusion matrix, or sample detections -->
![Model results](images/results.png)

## 💻 Tech Stack

`Python` · `[TensorFlow / PyTorch]` · `OpenCV` · `Arduino (C/C++)` · `ThingSpeak` · `[Twilio]` · `Proteus` · `Fritzing` · `Autodesk Inventor`

## 🚀 Getting Started

### Hardware
1. Assemble the components following the wiring diagram (`images/architecture.png`).
2. `[Note any calibration or wiring steps specific to your build.]`

### Software
```bash
git clone https://github.com/SaymaSJ/[your-repo-name].git
cd [your-repo-name]
pip install -r requirements.txt
```
- Upload the Arduino firmware (in `/firmware`) to your board.
- Run the disease-detection model:
```bash
python detect.py   # [adjust to your actual script name]
```

## 📊 Results

`[Briefly summarise what the system achieved — detection accuracy, what it could monitor, any field-test outcome.]`

## 📄 Related Publication

This work connects to my book chapter **"Sensors & Actuators"** in *Mechatronics: Fundamentals and Applications* (Springer Singapore, 2024). See my [Google Scholar](https://scholar.google.com/citations?hl=en&user=WTPD7AwAAAAJ) for related publications.

## 👩‍💻 Author

**Sayma Sultana Jhara** — Robotics & Automation Engineer
[LinkedIn](https://www.linkedin.com/in/sayma16/) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=WTPD7AwAAAAJ) · saymamte@gmail.com

## 📜 License

`[Choose a license — e.g. MIT — or state "All rights reserved."]`
