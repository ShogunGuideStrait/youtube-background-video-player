# YouTube Background Video Player

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:282828,100:FF0000&height=240&section=header&text=Youtube%20Background%20Video%20Player&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Turn%20Any%20Webpage%20Into%20A%20Cinematic%20Experience&descAlignY=58&descSize=22)

<div align="center">

![Version](https://img.shields.io/badge/version-3.4.0-FF0000?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-98.5K-282828?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20javascript-00E676?style=flat-square&logo=javascript&logoColor=black)

</div>

---

## 🎬 Why Your Hero Section Needs A Video

Think about the last website that truly impressed you. Was it a static image of a mountain? Or was it a looping, cinematic video of clouds rolling over the peaks?

The human eye is drawn to motion. A high-quality background video creates an emotional connection with the visitor before they even read a single word. It signals that your brand is premium, modern, and detail-oriented. This is why Apple uses it on every product page.

**YouTube Background Video Player** is a lightweight, open-source library that makes this cinematic effect accessible to everyone. It solves all the technical nightmares: hiding controls, removing branding, handling aspect ratios, and ensuring seamless looping. It is the fastest way to upgrade your landing page from "good" to "unforgettable."

<img width="1280" height="720" alt="maxresdefault - 2026-11-23T232758 601" src="https://github.com/user-attachments/assets/b2a86232-7713-4ef9-8c61-dab95ec27de6" />

---

## ⚡ What It Does (And Why It's Hard)

| The Problem | The Solution |
| :--- | :--- |
| YouTube shows play buttons and titles | We inject parameters to hide all UI |
| Videos don't autoplay on mobile | We force `mute=1` to trigger autoplay |
| Aspect ratio breaks on resize | We use CSS `object-fit` and a dynamic resizer |
| The video ends and freezes | We use the `playlist` parameter for infinite loops |
| YouTube branding is visible | We use `transform: scale(1.2)` to crop it out |

---

## ✨ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Full-Screen Video** | The video covers the entire background seamlessly |
| **No Controls** | Hides all YouTube UI elements for a clean look |
| **Auto-Loop** | The video loops forever without user interaction |
| **Responsive** | Automatically scales to any screen size |
| **Lightweight** | Under 5KB minified and gzipped |
| **Framework Support** | Vanilla JS, React, and Vue versions included |

---

<div align="center">

### 🔗 Ready to go cinematic?

[![Get Player](https://img.shields.io/badge/🎬_GET_PLAYER-282828?style=for-the-badge&logoColor=white)](https://share.google/iL5BqfmHeiVqHH8H4)

</div>

---

## ⚙️ Quick Setup

You can use the library via CDN or install it via npm.

```bash
# Step 1: Install via npm
npm install youtube-background-player

# Step 2: Import the library
import { YoutubeBackground } from 'youtube-background-player';

# Step 3: Initialize the player
new YoutubeBackground({
  element: document.getElementById('hero'),
  videoId: 'dQw4w9WgXcQ',
  mute: true,
  loop: true,
});
```

Once initialized, your `#hero` div will be filled with the looping YouTube video. You can add text and buttons on top of it using CSS `position: absolute`.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-FF0000?style=for-the-badge&logoColor=white)](https://share.google/iL5BqfmHeiVqHH8H4)

</div>

---

## 🧠 Under The Hood: The YouTube Iframe API

How do you embed a YouTube video without the controls? You use the **YouTube Iframe API**.

The API allows you to load a video with specific parameters. We use `?autoplay=1&mute=1&controls=0&loop=1&playlist={videoId}&showinfo=0`. The `mute=1` is critical because modern browsers block autoplaying videos with sound.

We also use CSS to hide the YouTube branding. We apply a `transform: scale(1.2)` to the iframe, which pushes the YouTube logo and title bar outside the visible area. This creates the illusion of a perfectly seamless video.

---

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube_API-FF0000?style=flat-square&logo=youtube&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We believe that the web should be beautiful. If you have added a new feature, improved the resizer, or found a bug in the iframe integration, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-feature`).
3. **Commit** your changes (`git commit -m 'Add new feature'`).
4. **Push** to the branch (`git push origin feature/new-feature`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your websites, ask for help with video IDs, and discuss the latest trends in web design.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@youtube-bg.dev.

---

<div align="center">

### ⭐ If this library beautifies your site, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/youtube-background-video-player)

---

### 🚀 Start building today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00E676?style=for-the-badge&logoColor=black)](https://share.google/iL5BqfmHeiVqHH8H4)

<sub>Crafted with precision and ❤️ by the YouTube Background Video Player community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,100:282828&height=120&section=footer)

</div>