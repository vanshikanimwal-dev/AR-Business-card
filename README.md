AR Business Card

An interactive Augmented Reality (AR) Business Card built using Unity (2022.3.6f2) and AR technologies. This project transforms a traditional business card into an immersive digital experience where users can scan a card and view 3D content, animations, and interactive elements directly in real-world space.

1. Project Overview

The AR Business Card enhances personal branding by overlaying digital content on top of a physical card using a smartphone camera. When the card is detected, virtual elements such as 3D models, social media links, portfolio previews, or contact buttons appear in AR.

This project demonstrates practical use of:

AR Foundation

Image Tracking

3D Asset Integration

UI Interaction in AR

Real-time rendering

2. Features

Image-based tracking of a printed business card

3D model visualization anchored to the card

Interactive UI elements (buttons for portfolio, LinkedIn, GitHub, etc.)

Smooth animations for enhanced user experience

Mobile AR support (Android)

Clean and optimized scene structure

3. Tech Stack

Unity 2022.3.6f2 (LTS)

AR Foundation

ARCore (for Android)

C#

Blender (for 3D assets)

Git for version control

4. How It Works

The camera scans the physical business card.

The AR system detects the reference image using image tracking.

A 3D prefab is instantiated at the tracked position.

UI elements are rendered in world space.

User interactions trigger external links or animations.

5. Project Structure
AR-Business-Card/
│
├── Assets/
│   ├── AR/
│   ├── Prefabs/
│   ├── Scripts/
│   ├── Scenes/
│   └── 3DModels/
│
├── ProjectSettings/
└── Packages/

6. Setup Instructions
Prerequisites

Unity 2022.3.6f2 installed

Android Studio installed

ARCore-supported Android device

USB debugging enabled on device

Steps

Clone the repository:

git clone <repository-link>


Open the project in Unity Hub.

Switch platform to Android.

Connect your ARCore-supported device.

Build and Run the project.

7. Use Case

Personal branding

Portfolio demonstration

Networking events

Career fairs

AR-based marketing solutions

8. Future Enhancements

Cloud-based dynamic content updates

Web-based AR version (WebXR)

Analytics integration

Multi-language support

Interactive 3D portfolio gallery

9. Learning Outcomes

Through this project, the following concepts are applied:

Understanding AR coordinate systems

Implementing image tracking

Managing AR anchors

Optimizing 3D assets for mobile

Designing intuitive AR UI

10. Demo

Add screenshots, demo video link, or APK link here.

11. License

This project is for educational and portfolio purposes.

12. Author

Developed as an AR-based interactive portfolio solution using Unity and AR technologies.
