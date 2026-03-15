# ✨ AuraFinder

![image alt](https://github.com/ErdemBuyukcinar/Aura-Finder/blob/a807fc5ad73a23a6aba4bb93c074010631a9f31a/aurafinder.png)

**AuraFinder** is a sleek, React-powered mobile application that analyzes spiritual energy signatures through digital imaging.

![image alt](https://github.com/ErdemBuyukcinar/Aura-Finder/blob/3915ca01e08e3a450ee985239075e72c17dbdb02/main-page.png)

## 🚀 Overview
By processing portraits via live camera or gallery upload, the app uses a **deterministic hashing algorithm** to generate a unique aura color and a personalized "Daily Mantra" and with Spotify API app gives a music for your "Daily Mantra".

![image alt](https://github.com/ErdemBuyukcinar/Aura-Finder/blob/3915ca01e08e3a450ee985239075e72c17dbdb02/daily.png)


## 💎 Key Features
* **Deterministic Analysis:** Ensures consistent energy results for the same visual input.
* **Native Gallery Export:** High-fidelity result rendering (3x scale) saved directly to Android's local gallery.
* **Android 13+ Optimized:** Fully compatible with modern granular media permissions and restricted storage protocols.
* **Dynamic UI:** Modern design featuring blurred backdrop-filters and mirrored camera previews.

## 🛠️ Tech Stack
* **Core:** React 18 (Vite) & Ionic Capacitor 6.
* **Styling:** Tailwind CSS v4 (HEX-optimized for rendering compatibility).
* **Graphics:** `html2canvas` for precise UI-to-image conversion.

## 🏗️ Technical Challenges Overcome
* **Rendering Optimization:** Resolved `oklch` color function limitations in `html2canvas` by implementing a HEX-variable theme bridge.
* **Build Stability:** Fixed complex Gradle build failures related to corrupted zip headers.
* **Native Integration:** Synchronized web-based permission requests with Android's native runtime security layer.

---
&copy; 2026 Erdem Buyukcinar
