# Project MEDI 🩺🧠

An advanced, immersive VR research platform engineered in Unreal Engine. **Project MEDI** bridges the gap between immersive game simulations and biometric feedback, utilizing a custom C++ framework and external biometric API integrations to create a dynamically adaptive, emotion-responsive virtual environment.

---

## 🚀 Key Features

- **Biometric Integration & Core API:** Connects real-time physiological data streams directly to the simulation logic.
- **Emotion-Responsive Environment:** Automatically shifts lighting, environmental shaders, audio ambiance, and NPC interaction states based on calculated user stress, focus, or anxiety thresholds.
- **VR Optimization:** Tailored for seamless high-framerate performance inside modern VR headsets (e.g., Meta Quest/SteamVR tracking standards).
- **C++ Native Architecture:** High-performance systems layout handling rapid sensor data interpretation without hitching the main render thread.

---

## 🎬 Project Preview

### System Overview & Gameplay Demonstration
*Below is a video walkthrough demonstrating the real-time environmental scaling based on simulation parameters.*

https://github.com/konaindevadnan/Konain_Adnan_Project-MEDI-/blob/main/Konain%20FYP%20FINAL%20VIDEO%20Medi.mp4

### Visual Showcases
<p align="center">
  <img src="Konain FYP FINAL VIDEO Medi.png" width="48%" alt="Main Simulation Environment" />
  <img src="Code Example/Convai API Used.png" width="48%" alt="Convai API Integration & NPC Logic" />
</p>

---

## 🛠️ Technical Stack & Architecture

- **Engine:** Unreal Engine (5.x recommended)
- **Languages:** C++ (Core Systems, API Interfacing) & Blueprints (Gameplay scripting, UI Event Handling)
- **Target Hardware:** VR Headsets (Oculus/Meta XR Plugin) + Supported Biometric Sensor Hardware
- **Core Integrations:** Convai API for intelligent, responsive NPC interactions.
- **Key Concepts Implemented:** Multi-threaded data parsing, dynamic material instances, state-machine driven environmental blending.

---

## 📦 Getting Started

### Prerequisites
- **Unreal Engine 5.x** installed via Epic Games Launcher or source.
- **Visual Studio 2022** (with C++ Game Development workloads enabled).
- Hardware-specific VR runtimes (Oculus App or SteamVR).

### Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/konaindevadnan/Konain_Adnan_Project-MEDI-.git](https://github.com/konaindevadnan/Konain_Adnan_Project-MEDI-.git)
