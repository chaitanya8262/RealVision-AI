# 🤖 AI Object Detection

A real-time object detection web application built with **TensorFlow.js** and **COCO-SSD** model. Detects objects directly in the browser using your webcam — no server required!

---

## 🌟 Demo

> Open `index.html` in your browser and allow camera access to start detecting objects in real time.

---

## ✨ Features

- 🎥 Real-time object detection via webcam
- 🧠 Powered by TensorFlow.js (COCO-SSD model)
- 🌐 Runs 100% in the browser — no backend needed
- ⚡ Fast and lightweight
- 📱 Works on desktop and mobile browsers

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure & Video element |
| CSS3 | Styling & Layout |
| JavaScript | Logic & Detection |
| TensorFlow.js | Machine Learning in browser |
| COCO-SSD | Pre-trained object detection model |

---

## 📁 Project Structure

```
AI-Object-Detection-main/
│
├── index.html      # Main HTML file (entry point)
├── style.css       # Styling
├── video.js        # Camera & detection logic
├── README.md       # Project documentation
└── LICENSE         # License info
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge)
- Webcam / Camera access

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/AI-Object-Detection.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd AI-Object-Detection
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # OR use Live Server in VS Code
   ```

> ⚠️ **Note:** Some browsers block camera access on `file://` protocol. Use **VS Code Live Server** or any local HTTP server for best results.

---

## 🎯 How It Works

1. Browser accesses your webcam using `getUserMedia` API
2. Video frames are passed to the **COCO-SSD** model via TensorFlow.js
3. The model detects objects and returns bounding boxes with labels
4. Results are drawn on an HTML5 Canvas overlaid on the video

---

## 📦 COCO-SSD Model

The **COCO-SSD** (Common Objects in Context - Single Shot MultiBox Detector) model can detect **80 different object classes** including:

`person` · `car` · `cat` · `dog` · `laptop` · `phone` · `chair` · `bottle` · `book` · and many more!

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the terms in the [LICENSE](LICENSE) file.

---

