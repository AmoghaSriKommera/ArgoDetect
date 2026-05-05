# 🌿 AgroDetect AI

AI-Powered Smart Plant Disease Diagnosis System\
Built using **Transfer Learning (MobileNetV2)**, **PyTorch**, and
**Flask**

------------------------------------------------------------------------

## 🚀 Overview

AgroDetect AI is an intelligent web-based plant disease detection system
that allows users to upload leaf images and receive:

-   🌱 Disease Prediction
-   📊 Confidence Score Visualization
-   ⚠ Severity Level Assessment
-   💊 Treatment Recommendations
-   📈 Model Insights (Loss Curve, Confidence Chart, Confusion Matrix)
-   🧠 Model Architecture Summary
-   📄 Downloadable PDF Report
-   💬 Built-in AI Assistant

The system is designed for agricultural support, academic
demonstrations, and hackathon deployments.

------------------------------------------------------------------------

## 🧠 Model Details

-   **Base Model:** MobileNetV2 (Transfer Learning)
-   **Framework:** PyTorch
-   **Optimizer:** Adam
-   **Loss Function:** CrossEntropyLoss
-   **Training:** GPU (Google Colab)
-   **Validation Accuracy:** \~95%+

Supported Crops: - Tomato - Potato - Pepper

Total Classes: - 9 plant disease categories (including healthy leaves)

------------------------------------------------------------------------

## 🖥️ Tech Stack

### Backend

-   Flask
-   PyTorch
-   Torchvision
-   Matplotlib
-   Pillow

### Frontend

-   HTML5
-   CSS3 (Custom Dark Theme UI)
-   JavaScript

------------------------------------------------------------------------

## 📊 Features

### 🔍 Disease Detection

Upload a leaf image and receive: - Predicted disease class - Confidence
score with progress bar - Severity classification (Low / Medium /
High) - Structured explanation - Recommended treatment

------------------------------------------------------------------------

### 📈 Model Insights Page

Includes:

-   📉 Training Loss Curve
-   📊 Model Confidence Bar Chart
-   🔢 Confusion Matrix
-   🧠 Model Architecture Summary
-   Navigation between Report & Insights

------------------------------------------------------------------------

### 📄 PDF Report Download

Users can download a structured diagnostic PDF containing: - Uploaded
image - Prediction details - Confidence score - Severity level -
Treatment recommendation

------------------------------------------------------------------------

### 💬 AI Assistant

Built-in assistant that: - Answers plant-related queries - Suggests
treatment best practices - Explains predictions

(Offline rule-based intelligent responses)

------------------------------------------------------------------------

## 🗂️ Project Structure

    AgroDetect/
    │
    ├── static/
    │   ├── css/
    │   ├── images/
    │   ├── uploads/
    │
    ├── templates/
    │   ├── index.html
    │   ├── report.html
    │   ├── insights.html
    │   ├── chatbot.html
    │
    ├── model.pth
    ├── app.py
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## ⚙️ How to Run Locally

### 1️⃣ Clone Repository

    git clone <your-repo-link>
    cd AgroDetect

### 2️⃣ Create Virtual Environment

    python -m venv venv
    venv\Scripts\activate

### 3️⃣ Install Dependencies

    pip install -r requirements.txt

### 4️⃣ Run Application

    python app.py

Open in browser:

    http://127.0.0.1:5000

------------------------------------------------------------------------

## 🎨 UI Highlights

-   Minimal Dark Mode Theme (#0a161c)
-   Glass-style cards
-   Smooth button transitions
-   Clean spacing layout
-   Structured report display
-   Professional hackathon-ready UI

------------------------------------------------------------------------

## 📌 Future Improvements

-   Real-time dataset expansion
-   Cloud deployment (AWS / Render)
-   Multi-language support
-   Real agricultural field testing
-   IoT integration

------------------------------------------------------------------------

## 👩‍💻 Author

**Project by Amogha Vyshnavi Aiman**\
Built for Hackathon \| AI + Agriculture Innovation

------------------------------------------------------------------------

## 📜 License

This project is for academic and demonstration purposes.
