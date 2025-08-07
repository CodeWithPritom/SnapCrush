# 🤳 SnapCrush – AI-Powered Face Filter App

Welcome to **SnapCrush**, a modern, elegant, and fun web-based **Snapchat-style face filter** app built using HTML, CSS, JavaScript, and **MediaPipe Face Mesh**! 🎭

![SnapCrush Demo](https://github.com/your-username/your-repo/assets/demo.gif)

---

## 🚀 Features

- 🧠 **AI Face Tracking** with MediaPipe
- 🔁 **Camera Flip Support** (Front & Rear)
- 🐱🐶🐰 **Fun Filters** – Add your own PNG overlays!
- 📸 **One-Click Capture**
- 📂 **Upload Your Own Images** for personalized filters
- 📱 Fully **responsive**, optimized for mobile & desktop
- 🎨 Elegant and **glassmorphism UI design**
- ⚡ **Fast and lightweight** (No backend required!)

---

## 🌐 Live Demo

🔗 [Click here to try SnapCrush in your browser!](https://codewithpritom.github.io/SnapCrush/)

> **Note**: Works best on Chrome and Safari with camera permissions enabled.

---

## 📸 Screenshots

| Mobile View | Upload Panel | Filters Carousel |
|------------|--------------|------------------|
| ![Mobile](assets/mobile-view.png) | ![Upload](assets/upload-panel.png) | ![Filters](assets/filters-carousel.png) |

---

## 🛠️ Technologies Used

| Tech Stack     | Purpose                             |
|----------------|-------------------------------------|
| HTML5 + CSS3   | Structure & Styling (Glass UI)      |
| JavaScript     | App Logic & Interactivity           |
| MediaPipe      | Face Mesh Tracking (Google)         |
| Webcam API     | Accessing camera streams            |
| FileReader API | Loading PNG overlays                |
| GitHub Pages   | Hosting (optional)                  |

---

## 📦 Libraries & CDNs

```html
<!-- MediaPipe Libraries -->
<script src="https://cdn.jsdelivr.net/npm/@mediapipe/face_mesh/face_mesh.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@mediapipe/camera_utils/camera_utils.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@mediapipe/drawing_utils/drawing_utils.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@mediapipe/control_utils/control_utils.js"></script>
````

---

## 🧩 How to Use

1. **Clone the repo:**

   ```bash
   https://github.com/CodeWithPritom/SnapCrush.git
   cd snapcrush
   ```

2. **Run locally (optional):**
   Open `index.html` in your browser.

3. **Or deploy using GitHub Pages.**

---

## ✨ Upload Custom Filters

You can upload your own **cat 🐱**, **dog 🐶**, or **bunny 🐰** overlays as transparent PNGs. Drag and drop or select files through the 📂 button.

---

## 🎯 Responsive UI

SnapCrush is fully optimized for:

* 📱 Mobile Phones
* 💻 Desktops
* 📷 Front/Rear Cameras

---

## 💡 Pro Tips

* Use **high-res transparent PNGs** for filters.
* Mobile camera flipping is supported via `facingMode`.
* Filters scale and rotate based on your face orientation.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📃 License

MIT © [CodeWithPritom](https://github.com/CodeWithPritom)

---

## 🔥 Fun Fact

> Built using **real-time face tracking AI** and sprinkled with ✨ web magic ✨.

---

📌 **Stay tuned** for AR filter packs, sticker packs, and full mobile PWA support!



To make this more **interactive and visually engaging**:

1. **Add assets to your repo**:
   - `/assets/demo.gif` – A screen-recorded GIF of the app.
   - `/assets/mobile-view.png`, `/upload-panel.png`, etc.

2. **Enable GitHub Pages**:
   - Deploy your HTML project and link it in the README under **Live Demo**.

3. **Add Shields.io badges** (optional):
   ```md
   ![Status](https://img.shields.io/badge/status-active-brightgreen)
   ![License](https://img.shields.io/github/license/your-username/snapcrush)
   ![Made with](https://img.shields.io/badge/Made%20with-MediaPipe-blue)
