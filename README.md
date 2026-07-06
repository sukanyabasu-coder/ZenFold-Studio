# 🦢 ZenFold Studio

An AI-assisted interactive origami web experience that combines **computer vision**, **hand gesture recognition**, **voice commands**, and **3D graphics** to create a unique browser-based paper folding experience.

Built using **Google Gemini** through prompt engineering and modern web technologies.

---

## ✨ Features

- ✋ Real-time hand gesture recognition using MediaPipe Hands
- 📄 Interactive origami folding experience
- 🤏 Pinch gesture detection for folding actions
- 🎙️ Voice commands for navigation
- 🖱️ Mouse controls as an alternative to gestures
- 🔄 Restart current origami anytime
- 🏠 Return to the home screen using voice or mouse
- 🎨 Modern glassmorphism-inspired user interface
- ⚡ Runs entirely in the browser without a backend

---

## 🎮 Controls

### Hand Gestures
- Hover your hand over the highlighted fold point.
- Pinch using your thumb and index finger to perform the fold.
- Continue following each guided step until the origami is complete.

### Voice Commands
- **Home** → Return to the home screen
- **Restart** → Restart the current origami model

### Mouse Controls
- Previous Step
- Next Step
- Restart

---

## 📷 Demo

-Screenshots provided in the repo itself

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript (ES6+)

### 3D Graphics
- Three.js
- WebGL

### Computer Vision
- MediaPipe Hands
- MediaPipe Camera Utilities

### Animation
- GSAP (GreenSock Animation Platform)

### AI & Browser APIs
- Google Gemini (Prompt Engineering)
- Web Speech API
- Speech Synthesis API

---

## 🚀 Getting Started

1. Download or clone this repository.
2. Open `index.html` in Google Chrome.
3. Allow camera and microphone permissions when prompted.
4. Start folding!

---

## 📌 Current Origami Models

- Crane
- Boat
- Butterfly

*(More models will be added in future updates.)*

---

## ⚠️ Known Limitation

The current version may request camera permission multiple times and microphone permission more than once during startup.

This is a browser permission handling issue that will be improved in future versions to provide a smoother user experience.

---

## 💡 Future Improvements

- Improve permission handling
- Add additional origami models
- Better gesture recognition accuracy
- Smoother folding animations
- Mobile browser support
- Progress tracking
- Sound effects
- Difficulty levels

---

## 🤖 Development Note

This project was developed using **Google Gemini** as an AI coding assistant through iterative prompt engineering.

I designed the project concept, interaction flow, features, testing process, and continuously refined AI-generated code to build the final application.

---

## 📄 License

This project is licensed under the MIT License.
