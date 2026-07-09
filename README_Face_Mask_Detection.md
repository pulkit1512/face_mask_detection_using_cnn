# 😷 Face Mask Detection using Transfer Learning & FastAPI

> An end-to-end Deep Learning project for real-time face mask detection using Transfer Learning, deployed with FastAPI and an interactive web interface.

---

# 🌟 Features

## 🏠 Home Page
- Hero banner with project introduction
- Overview of the application
- Quick navigation cards
- Responsive modern UI

## 📖 About Page
- Why face mask detection is important
- COVID-19 lessons and future pandemic preparedness
- Real-world applications in hospitals, airports, schools, offices, malls and public transport

## 🧠 Transfer Learning Page
Explain:
- What is Transfer Learning?
- Why not train from scratch?
- Benefits:
  - Faster training
  - Higher accuracy
  - Less data required
  - Lower computational cost

Illustrate the architecture:

Input Image
↓
Resize & Normalize
↓
Data Augmentation
↓
Pretrained CNN
↓
Global Average Pooling
↓
Dense Layer
↓
Dropout
↓
Softmax
↓
Prediction

---

# 🔄 Complete Model Pipeline

1. Dataset Collection
2. Image Preprocessing
3. Train/Validation/Test Split
4. Data Augmentation
5. Load Pretrained CNN
6. Freeze Base Layers
7. Train Classification Head
8. Fine-Tune Model
9. Evaluate Performance
10. Save Model
11. Deploy with FastAPI
12. Real-Time Prediction

---

# 🌐 Website Functionalities

## 📤 Upload Image
Upload JPG, PNG or JPEG images.

## 📷 Webcam Prediction
- Open webcam
- Capture photo
- Predict instantly

## 🤖 Prediction Result
Display:
- With Mask 😷
- Without Mask ❌

## 📊 Confidence Score
Example:

Prediction: With Mask

Confidence: 99.12%

## 🖼 Image Preview
Display uploaded/captured image beside prediction.

## 📈 Performance Dashboard
Include:
- Training Accuracy Graph
- Validation Accuracy Graph
- Training Loss
- Validation Loss
- Confusion Matrix
- Precision
- Recall
- F1 Score

## 📜 Prediction History
Store recent predictions with:
- Date & Time
- Prediction
- Confidence

## 📄 Download Report
Generate a PDF containing:
- Uploaded Image
- Prediction
- Confidence
- Timestamp

## 🌙 Dark / Light Mode

## ⚡ Loading Animation

## 📱 Responsive Design

## 📚 API Documentation
FastAPI automatically provides:
- /docs
- /redoc

---

# 🚀 Why Face Mask Detection?

Future pandemics may again require protective equipment.

This system helps:
- Hospitals
- Airports
- Schools
- Offices
- Railway Stations
- Shopping Malls
- Manufacturing Industries

Benefits:
- Automatic compliance monitoring
- Reduced manual inspection
- Faster screening
- Better public safety

---

# 🧰 Technology Stack

Backend:
- FastAPI
- Uvicorn

Deep Learning:
- TensorFlow
- Keras

Computer Vision:
- OpenCV

Frontend:
- HTML
- CSS
- JavaScript

Others:
- NumPy
- Pillow

---

# 📂 Suggested Project Structure

```text
Face-Mask-Detection/
│
├── app.py
├── predict.py
├── requirements.txt
├── model/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── transfer_learning.html
│   ├── pipeline.html
│   ├── dashboard.html
│   └── history.html
├── uploads/
├── reports/
├── README.md
└── notebook.ipynb
```

---

# 🔁 User Workflow

Home Page

↓

Upload Image **OR** Open Webcam

↓

Image Preprocessing

↓

Transfer Learning Model

↓

Prediction

↓

Confidence Score

↓

Result + History

↓

Optional PDF Download

---

# 📊 Model Performance

Replace these placeholders with your results.

| Metric | Value |
|--------|------:|
| Training Accuracy | XX% |
| Validation Accuracy | XX% |
| Test Accuracy | XX% |
| Precision | XX% |
| Recall | XX% |
| F1 Score | XX% |

---

# 💡 Future Improvements

- Real-time video detection
- Multiple face detection
- Face detection before classification
- Mobile App
- Cloud deployment
- Docker support
- User authentication
- Admin dashboard
- Analytics dashboard
- PPE detection
- Helmet detection
- Social distancing monitoring
- Email alert system
- Attendance integration

---

# 🎓 Learning Outcomes

This project demonstrates:
- CNN fundamentals
- Transfer Learning
- Image preprocessing
- Data augmentation
- Model evaluation
- FastAPI deployment
- REST API development
- Frontend integration
- Webcam integration
- End-to-end Deep Learning deployment

---

# ▶️ Run the Project

```bash
pip install -r requirements.txt
```

```bash
uvicorn app:app --reload
```

Open:

http://127.0.0.1:8000

API Docs:

http://127.0.0.1:8000/docs

---

# 👨‍💻 Author

**Pulkit Sharma**

AI & Machine Learning Student

Built using TensorFlow, Keras, FastAPI and OpenCV.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
