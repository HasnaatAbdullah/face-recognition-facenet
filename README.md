# face-recognition-facenet
Implemented a deep learning-based face recognition and verification system using FaceNet and one-shot learning. Generates 128-dimensional face encodings and performs 1:1 face verification and 1:K face recognition.
# 👤 Face Recognition using FaceNet

This project implements a **deep learning-based face recognition system** using **FaceNet**.  
It uses a **pre-trained Inception-based model** to encode faces into **128-dimensional vectors** and applies **one-shot learning** for face verification and recognition.

---

## 🚀 Project Overview

Face recognition can be divided into two tasks:

### **1. Face Verification** (1:1 Matching)
- Checks if two images belong to the **same person**.
- Used in scenarios like **passport control** or **phone unlocking**.

### **2. Face Recognition** (1:K Matching)
- Identifies **who the person is** among a database of known faces.
- Commonly used in **attendance systems, security systems, and access control**.

This project uses **FaceNet** to learn embeddings and compare them using a **distance metric**.  

---

## 🧠 Key Features

- Generates **128-dimensional face encodings** using FaceNet.
- Uses **triplet loss** to train the model for high accuracy.
- Performs **one-shot learning** for face recognition.
- Handles **1:1 verification** and **1:K recognition** scenarios.
- Supports adding new faces to the database dynamically.

---

