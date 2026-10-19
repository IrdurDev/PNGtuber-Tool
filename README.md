[![Itch.io](https://img.shields.io/badge/Itch-%23FF0B34.svg?style=for-the-badge&logo=Itch.io&logoColor=white)](https://irdurdev.itch.io/pngtuber-tool)
[![Latest Release](https://img.shields.io/github/v/release/IrdurDev/PNGtuber-Tool?sort=semver&display_name=tag)](https://github.com/IrdurDev/PNGtuber-Tool/releases/latest)
![Windows 10 x32](https://img.shields.io/badge/Windows_10-x32-blue)
![Windows 10 / 11 x64](https://img.shields.io/badge/Windows_10_%2F_11-x64-blue)
![macOS 10.13+ Intel](https://img.shields.io/badge/macOS-10.13%2B_Intel-blue)



# PNGtuber 🎭

> A lightweight, lightweight-reactive avatar tool for streamers, content creators, and gamers.

**PNGtuber** lets you use static images (PNG, JPG, etc.) as animated avatars. It listens to your voice via microphone in real-time and brings your character to life with dynamic movement (jumping, stretching, swaying, glowing, and more) based on your audio intensity—no camera, 3D tracking, or heavy software required!

---

## ✨ Features

- **🎙️ Real-Time Voice Reaction:** Avatar movement is proportional to audio volume, equipped with an adjustable decibel (dB) threshold to easily filter out background noise.
- **🖼️ Flexible Image States:** Supports up to 3 image states: **Idle**, **Speaking** (mouth open), and **Blinking**. Only the *Idle* image is required to get started!
- **🎨 Highly Customizable Animations:**
  - Active animations: Elastic bounce-jump, stretching, scaling up, swaying, shaking, and glowing.
  - Idle effects: Subtle breathing and randomized blinking.
- **🔌 Automatic Microphone Detection:** Instantly detects connected audio devices on launch and dynamically updates when devices are plugged or unplugged. Switch mics on the fly!
- **📺 Stream-Ready Backgrounds:** Toggle between **Transparent**, **Green Screen (Chroma Key)**, or a custom color for seamless capture in OBS Studio, Streamlabs, or other software.
- **📐 Adaptable Control Panel:** Responsive layout supporting both portrait and landscape modes, with draggable height adjustments.
- **💾 Import / Export Settings:** Save your preferred configurations and export/import them as external files.
- **🧪 Test Mode:** Built-in voice input simulation to let you preview and tune your animation settings without having to talk continuously.

---

## 🚀 How to Use

1. **Launch:** Open the app and grant microphone permissions.
2. **Import:** Upload your character image(s) or drag and drop them directly into the app window.
3. **Calibrate:** Adjust the audio sensitivity threshold so the avatar only reacts to your voice.
4. **Customize:** Tweak the animation styles, intensity, and idle behaviors to your liking.
5. **Stream:**
   - Press **`H`** to hide/show the control panel UI.
   - Capture the window in OBS (or preferred streaming software). If using a green background, apply a *Chroma Key* filter.
   - Press **`C`** to center the PNGtuber image.

---

## 💻 System Requirements

| Platform | Requirements | Notes |
| :--- | :--- | :--- |
| **macOS** | macOS 10.13 High Sierra or later | Intel Processor. *Apple Silicon (M1/M2/M3/M4) models require Rosetta 2.* |
| **Windows** | Windows 10 (32-bit) & Windows 10/11 (64-bit) | Direct executable. |
| **Web Version** | Any modern web browser | Lightweight original HTML/JS build. |

> ⚠️ **Windows Warning Note:**  
> Windows users may encounter a *SmartScreen / Potentially Unwanted Application* security warning upon execution. Because this project is not digitally signed with an expensive code-signing certificate, Windows flags it automatically. The software is completely safe, but execution requires clicking *"Run anyway"*.

---

## 🤖 Built With AI Assistance

This application was developed in collaboration with **Claude** (Anthropic). 
- **Claude:** Wrote the core codebase, designed logic algorithms, and handled application packaging based on iterative prompting.
- **Human Developer:** Concept, logic testing, UX design, parameter calibration, and fine-tuning.
