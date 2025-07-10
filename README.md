# 🧠 COCO-SSD Object Detection App (TensorFlow.js + Vite)

A simple real-time object detection web app using **TensorFlow.js** and the **COCO-SSD** pre-trained model. Built with vanilla JavaScript and powered by Vite for fast development.

## 🚀 Features

- Real-time object detection using webcam
- Detects 80 common objects (COCO dataset)
- Built with modern tools: Vite, TensorFlow.js
- Minimal UI with bounding boxes and labels

## 🛠️ Technologies Used

- [@tensorflow/tfjs](https://www.npmjs.com/package/@tensorflow/tfjs)
- [@tensorflow-models/coco-ssd](https://www.npmjs.com/package/@tensorflow-models/coco-ssd)
- [Vite](https://vitejs.dev/)

## 📦 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# 2. Install dependencies
npm install

# 3. Run the development server
npm run dev
```

Then open your browser at `http://localhost:5173` and allow webcam access.

## 🌐 Deploy to GitHub Pages

Optional: to deploy it as a live site.

```bash
# Install GitHub Pages deploy tool
npm install --save-dev gh-pages

# Add these to package.json
# "homepage": "https://your-username.github.io/your-repo-name",
# and add a deploy script:
# "deploy": "vite build && gh-pages -d dist"

# Build and deploy
npm run deploy
```

Live site: [https://your-username.github.io/your-repo-name](https://your-username.github.io/your-repo-name)

## 📸 Screenshot

![screenshot](screenshot.png)

## 🧠 Model Info

This app uses the COCO-SSD model which detects:
- People, animals, vehicles, furniture, and more.
- Based on the [COCO dataset](https://cocodataset.org/#home)

## 📄 License

MIT © [Your Name](https://github.com/your-username)
