# MediScan 

MediScan is an **AI-powered healthcare application** that digitizes handwritten doctor prescriptions using **OCR + NLP**, extracts structured medical information, and enables **secure medicine ordering and delivery**. The project is designed to reduce prescription errors, improve accessibility, and streamline the medicine delivery process.

---

## 🚀 Project Overview

Doctors often write prescriptions by hand, which can be difficult for patients and pharmacists to read correctly. MediScan solves this problem by:

* Converting handwritten prescriptions into **machine-readable text**
* Extracting **medicine names, dosage, frequency, and duration**
* Verifying user identity using **age & emotion detection** (for safe medicine delivery)
* Allowing users to **search and order medicines online**

This project combines **Computer Vision, NLP, and Full-Stack Development** into a single real-world healthcare solution.

---

## 🧠 Key Features

### 🔍 Prescription Digitization

* Upload prescription images (JPEG/PNG)
* Image preprocessing using **OpenCV**
* Text extraction using **Tesseract OCR**

### 🧾 NLP-Based Medical Data Extraction

* Named Entity Recognition (NER) using **spaCy**
* Extracts:

  * Medicine names
  * Dosage
  * Frequency
  * Duration

### 🧑‍⚕️ Age & Emotion Detection (Security Layer)

* Face detection using OpenCV
* Age group classification
* Emotion detection for identity verification
* Restricts medicine delivery in unsafe or mismatched cases

### 💊 Medicine Search & Ordering

* Medicine search with filters
* Structured prescription view
* Order medicines directly from digitized data

### 🌐 User Interface

* Built with **Streamlit** (initial version)
* Simple, clean, and dark-theme friendly UI
* Real-time results and alerts

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### Backend & AI

* Python
* OpenCV
* Tesseract OCR
* spaCy (NLP)
* NumPy, Pandas

### Machine Learning

* Image preprocessing & enhancement
* OCR pipeline
* NLP-based entity extraction
* Age & emotion detection models

---

## 🏗️ System Architecture

1. User uploads prescription image
2. Image preprocessing (grayscale, thresholding, noise removal)
3. OCR extracts raw text
4. NLP processes text and extracts medical entities
5. Face-based age & emotion verification
6. Medicine data displayed in structured format
7. User places medicine order

---

## 📊 Use Cases

* Digitizing handwritten prescriptions
* Reducing medical interpretation errors
* Assisting pharmacies with structured data
* Secure medicine delivery platforms
* Healthcare AI research projects

---

## 🔮 Future Enhancements

* Mobile app (Android/iOS)
* MERN stack web version
* Doctor & pharmacy dashboards
* Cloud deployment (AWS/GCP)
* Multi-language prescription support
* E-prescription integration

---

## 🎯 Learning Outcomes

* OCR & image preprocessing
* NLP for real-world text extraction
* Healthcare-focused AI system design
* Secure AI application development
* End-to-end project architecture

---

## 👨‍💻 Author

**Suyash**
B.Tech Computer Science (2022–2026)
AI | ML | Full Stack Development

---

## 📜 License

This project is licensed for educational and research purposes.

