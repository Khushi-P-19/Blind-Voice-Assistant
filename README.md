# 🤖 Advanced AI Vision Assistant

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge)
![Tesseract.js](https://img.shields.io/badge/Tesseract.js-1E88E5?style=for-the-badge)

**Real-time Object Detection • Scene Description • OCR • Distance Estimation**  
**Voice-Controlled AI Assistant for Visually Impaired People**

---

## 📝 Problem Statement

Visually impaired individuals face major challenges in understanding their surroundings independently.  
Traditional aids (white cane, guide dog) are limited and cannot:
- Identify objects with distance
- Read printed text
- Describe complex scenes
- Answer natural voice questions

Existing apps are either slow, require internet, or need expensive hardware.  
There is a need for a **free, browser-based, real-time vision assistant** that works on any laptop/phone with a camera.

---

## ✨ Solution

**Advanced AI Vision Assistant** is a single-file web application that turns any device camera into a smart assistant for the visually impaired.

It combines:
- Real-time object detection with distance
- AI-powered natural scene description
- OCR text reading
- Full voice conversation interface

Everything runs **directly in the browser** — no installation, no server, fully private and offline-capable (except for optional AI description).

---

## 🚀 How It Works (Step-by-Step)

1. **Open the HTML file** in Chrome/Edge → Click “Start Vision”
2. **Camera activates** (rear camera preferred)
3. **Real-time Detection**  
   - COCO-SSD model detects objects every 1.5 seconds
   - Draws bounding boxes + confidence + distance on screen
4. **Voice Commands**  
   - Say “What do you see?”, “Describe the scene”, “Read the text”, “How far is the person?”
5. **AI Responses**  
   - Scene description using BLIP-2 (Hugging Face)
   - OCR using Tesseract.js
   - Distance estimation using calibrated formula
6. **History & Live Display**  
   - All conversations saved
   - Currently detected objects shown with emojis and distances

---

## 🔥 Key Features

- Real-time object detection (80+ classes) with bounding boxes
- Distance estimation (in meters) using focal length formula
- AI scene description with context (e.g., “person working on laptop”)
- OCR text reading with grayscale enhancement
- Full voice interaction (speak & listen)
- Live detection grid with emojis
- Conversation history
- Processing indicators and status bar
- Works offline after first load (except AI description)

---

## 🛠️ Technologies Used

| Technology              | Purpose                              |
|-------------------------|--------------------------------------|
| **TensorFlow.js**       | COCO-SSD object detection            |
| **Tesseract.js**        | OCR text reading                     |
| **Hugging Face API**    | BLIP-2 & BLIP-large scene description|
| **Web Speech API**      | Voice recognition & text-to-speech   |
| **Tailwind CSS**        | Modern responsive UI                 |
| **HTML5 Canvas**        | Real-time bounding box overlay       |

---
