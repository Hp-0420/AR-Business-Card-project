# 💼 AR Business Card using Unity, Vuforia & Ready Player Me

![AR Business Card](https://img.shields.io/badge/Platform-Unity-green?style=flat-square)
![AR Business Card](https://img.shields.io/badge/AR%20Engine-Vuforia-blue?style=flat-square)
![AR Business Card](https://img.shields.io/badge/Avatar-Ready%20Player%20Me-purple?style=flat-square)
![AR Business Card](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

## 📌 Project Overview

This project is an **Augmented Reality Business Card** built using **Unity**, **Vuforia**, and **Ready Player Me**. Upon scanning a physical business card, the application overlays a **3D avatar**, displays user profile info (name, picture, and bio), and provides **interactive buttons** for visiting social media profiles—creating a futuristic and immersive networking experience.

> ✨ Imagine handing someone your card and having a **custom 3D avatar** pop up and introduce you, along with your social links right on their screen.

---

## 🧰 Tools & Technologies

| Technology | Purpose |
|-----------|---------|
| 🧠 Unity | Game engine used to build the AR experience |
| 🔍 Vuforia Engine | Image tracking and AR capabilities |
| 🧍‍♂️ Ready Player Me | Integration of customizable 3D avatars |
| 🎨 TextMeshPro | Rich text elements for UI |
| 📱 Android Platform | Target deployment platform |

---

## 🔗 Demo Video

🎥(https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXg1YjdqeWlsbTE5NzkzbDA2aWU3cmNneHd0ZXk5dW1mMHpuMmt3dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/u6axdBful4Z2fTblYF/giphy.gif)

## ✨ Features

- ✅ **Image-Based AR Trigger** using Vuforia
- ✅ **Real-time 3D Avatar** from Ready Player Me
- ✅ **Business Card Texture** rendered as a 3D plane
- ✅ **Dynamic UI**: name, bio, and profile picture
- ✅ **Interactive Social Media Buttons**
- ✅ **Link Manager Script** to open external URLs
- ✅ **Custom Intro Animations** for UI containers
- ✅ **Rotation Animation** for 3D Avatar
- ✅ **Responsive AR Interface** using World-Space Canvas
- ✅ **Extended Tracking** for better user experience
---

## 🔧 How It Works

### 📌 Image Tracking

- Used **Vuforia Engine** to recognize a physical business card as a marker.
- Created a target database in the Vuforia Developer Portal and imported it into Unity.
- When the target image is detected, a virtual UI and avatar are displayed.

### 🧍‍♂️ Avatar Integration

- Used **Ready Player Me SDK** to load a customizable avatar using a GLB URL.
- Enabled animation and disabled model caching for real-time updates.

### 🎨 Business Card Design

- Created a **3D Plane** and mapped it with a material that holds the business card texture.
- Added **diffuse shaders** for optimal visual output.

### 🖥️ User Interface

- World-space **Canvas** was added on top of the image target.
- UI elements include:
  - Profile picture
  - Full name and short bio
  - Social media buttons with logos

### 🖱️ Interactivity

- Buttons are linked using a **LinkManager.cs** script to open URLs in the default browser.
- All UI buttons are fully functional on Android devices.

### 🎞️ Animations

- Created **intro animations** for UI containers using Unity’s Animation system.
- These animations are triggered when the AR marker is detected.
- Disabled looping to ensure smooth, one-time transitions.

---

## 📂 Project Structure

```

Assets/
├── Avatars/
├── Materials/
├── Scripts/
│   ├── Rotate.cs
│   └── LinkManager.cs
├── UI/
│   ├── Canvas/
│   ├── Containers/
│   └── Buttons/
├── Vuforia/
├── Prefabs/
└── Scenes/

```

---

## 🧪 Demo & Testing

- Tested using Unity's **Play Mode with webcam**.
- Successfully displayed avatar and business card when target was detected.
- Verified button functionality opens correct URLs.
- Validated animations play correctly on detection.

---

## 📲 Future Improvements

* 📱 iOS Support & WebAR
* 📧 Contact Form Integration
* 🌐 Dynamic data from web APIs

---

## 🤝 Acknowledgements

- 🎥 Inspired by tutorial from **Priyanshu Bhattacharjee**
- 👾 Avatar integration powered by **Ready Player Me**
- 📡 AR functionality by **Vuforia Engine**

---

## 📬 Contact

If you liked the project or have questions, feel free to connect:

- 🔗 [LinkedIn](https://linkedin.com/in/yourusername)
- 📧 your.email@example.com

---

## 🌟 Star this repo

If you find this project helpful or inspiring, don’t forget to **⭐️ star** this repository and **share it** with others in the AR/VR community!

---
