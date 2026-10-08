[README.md](https://github.com/user-attachments/files/33189405/README.md)
# 🛋️ AR Furniture Placement & Visualization

<p align="center">
  <strong>Visualize. Place. Transform. Experience.</strong><br>
  An Android-based Augmented Reality application for visualizing furniture in real-world environments.
</p>

<p align="center">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Android-green?style=for-the-badge">
  <img alt="Unity" src="https://img.shields.io/badge/Engine-Unity-000000?style=for-the-badge&logo=unity&logoColor=white">
  <img alt="AR Foundation" src="https://img.shields.io/badge/AR-Foundation-blue?style=for-the-badge">
  <img alt="ARCore" src="https://img.shields.io/badge/AR-Google%20ARCore-orange?style=for-the-badge&logo=google">
  <img alt="C#" src="https://img.shields.io/badge/Language-C%23-purple?style=for-the-badge">
</p>

---

## 📌 Overview

**AR Furniture Placement & Visualization** is a mobile Augmented Reality application developed with Unity and AR Foundation. It lets users visualize virtual furniture directly inside their real surroundings using the smartphone camera.

The application detects real-world surfaces, places virtual furniture in the environment, and allows users to interact with the placed objects through touch gestures.

## ✨ Features

- 📷 Live AR camera view
- 🧭 Markerless AR
- 📐 Horizontal and vertical surface detection
- 🪑 Multiple furniture models
- 👆 Tap-to-place furniture
- ✋ Move placed furniture
- 🔄 Rotate furniture
- 🔍 Scale furniture with gestures
- 🗑️ Remove placed objects
- 💡 In-app hints and guidance
- 📱 Android / ARCore device support

## 🎯 Problem Statement

Users often find it difficult to judge whether furniture will suit their room before purchasing or arranging it. This project addresses the problem by allowing users to visualize virtual furniture directly in their real-world environment.

## 💡 Application Workflow

```text
Launch App
    ↓
Open Camera
    ↓
ARCore Tracks Environment
    ↓
Detect Real-World Surface
    ↓
Select Furniture
    ↓
Tap to Place 3D Model
    ↓
Move / Rotate / Scale
    ↓
View / Manage Furniture
    ↓
Remove or Replace Object
```

## 🧠 AR Technique

The project uses **markerless Augmented Reality with plane detection**. No printed marker, QR code, or image target is required.

```text
Camera + Sensors
       ↓
Google ARCore
       ↓
Plane Detection & Tracking
       ↓
AR Foundation
       ↓
AR Raycast
       ↓
3D Position & Orientation
       ↓
Virtual Furniture Placement
```

## 🏗️ System Architecture

```text
Android Smartphone
(Camera + Sensors)
        ↓
Google ARCore
(Tracking + Detection)
        ↓
AR Foundation
        ↓
Plane Detection + Raycasting
        ↓
Furniture Logic
(Select / Place / Move / Rotate / Scale / Remove)
        ↓
3D Furniture Assets
        ↓
Interactive AR Scene
```

## 🧩 Major Modules

| Module | Purpose |
|---|---|
| AR Tracking | Tracks device movement and understands the environment |
| Plane Detection | Detects horizontal and vertical surfaces |
| AR Placement | Places furniture on detected surfaces |
| Furniture Selection | Allows users to choose furniture |
| 3D Object Management | Manages virtual furniture objects |
| Gesture Interaction | Supports moving, rotating and scaling |
| Furniture Information | Displays furniture-related information |
| User Interface | Provides controls, status messages and hints |
| Object Removal | Removes placed furniture |
| Android / ARCore Integration | Runs the AR experience on supported devices |

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Development Engine | Unity |
| AR Framework | Unity AR Foundation |
| AR Provider | Google ARCore |
| Programming Language | C# |
| Platform | Android |
| 3D Content | Virtual furniture models |
| Development Environment | Unity Editor |

## 📂 Project Structure

```text
MebelAR/
├── Assets/
├── Packages/
└── ProjectSettings/
```

## 🚀 Getting Started

### Prerequisites

- Unity with Android Build Support
- Android SDK & NDK
- OpenJDK
- ARCore-supported Android device
- USB debugging enabled for direct device testing

### Setup

1. Clone the repository:

```bash
git clone https://github.com/AlexDim1/MebelAR.git
```

2. Open the project in Unity.
3. Allow Unity to import packages.
4. Confirm AR Foundation and Google ARCore XR Plugin are available.
5. Switch the build target to Android.
6. Open the main AR scene.
7. Connect an ARCore-supported Android device.
8. Build and run the application.

## 📱 User Controls

| Action | Result |
|---|---|
| Move phone slowly | Scan environment |
| Select furniture | Activate selected model |
| Tap surface | Place furniture |
| Drag / touch gesture | Move object |
| Rotation gesture | Rotate object |
| Pinch gesture | Scale object |
| Remove | Delete placed object |
| Hint | Show user guidance |

## 🧪 Testing

| Test Case | Status |
|---|---|
| Detect real-world surface | ✅ Pass |
| Select furniture | ✅ Pass |
| Place 3D furniture | ✅ Pass |
| Move furniture | ✅ Pass |
| Rotate furniture | ✅ Pass |
| Remove furniture | ✅ Pass |
| Display in-app hints | ✅ Pass |
| Track device movement | ✅ Pass |
| Test different furniture items | ✅ Pass |

## ⚠️ Challenges & Limitations

- Surface detection can take longer on visually weak surfaces.
- Low-light or reflective environments can reduce tracking quality.
- Placement accuracy depends on stable plane detection.
- Gesture interaction can become less smooth during unstable tracking.
- Complex 3D models can increase mobile performance requirements.
- Realistic appearance is limited without advanced lighting, shadows, reflections and occlusion.
- The application requires an ARCore-supported Android device.

## 🔮 Future Scope

- More realistic lighting, shadows, reflections and occlusion
- Larger furniture catalogue
- Furniture and room measurement
- Online furniture catalogue
- E-commerce integration
- Voice controls
- Advanced hand-gesture interaction
- Multiple furniture placement
- Save/load room layouts
- AI-based furniture recommendations

## 📸 Screenshots

Add your best screenshots here:

```text
1. AR Surface Detection
2. Furniture Placement
3. Furniture Interaction
4. Application Interface
```

> Recommended: make the first screenshot a real camera view showing furniture placed inside the room.

## 🎓 Academic Project

**Project:** AR Furniture Placement  
**Course:** Augmented Reality and Virtual Reality (ARVR)  
**Department:** Information Technology  
**Academic Year:** 2026–2027

### Team

- Husain Mistry
- Mikhail Saldanha
- Pranav Salian
- Tanish Shetty

### Guide

**Ms. Pratibha Rane** — Assistant Professor

## 📚 References

1. A. Dim, *MebelAR: An Android AR application for visualizing furniture items in the real world*, GitHub: https://github.com/AlexDim1/MebelAR
2. Unity Technologies, *AR Foundation Documentation*.
3. Unity Technologies, *Google ARCore XR Plugin Documentation*.
4. Google, *ARCore Fundamentals*.
5. Google, *ARCore Hit-Test Documentation*.
6. Google, *ARCore Content Placement Guidelines*.
7. Blender Foundation, *Blender Reference Manual*.

---

<p align="center">
  <strong>Built with Unity + AR Foundation + Google ARCore 💙</strong>
</p>
