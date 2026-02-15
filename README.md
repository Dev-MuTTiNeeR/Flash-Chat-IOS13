# ⚡️ Flash Chat iOS

Flash Chat is a lightweight, internet-based real-time messaging application. It allows users to securely create accounts, log in, and exchange messages instantly.

This project was developed to demonstrate proficiency in **MVC Architecture**, **Firebase Integration**, and **CocoaPods** dependency management within the iOS development ecosystem.

## 📱 App Screenshots

### 1. Authentication & Splash
<p align="center">
  <img src="https://github.com/user-attachments/assets/6b03240b-7692-4811-b7a4-a0c6fd6d9fbe" width="220" alt="Splash Screen">
  <img src="https://github.com/user-attachments/assets/03e88347-05b3-4106-bdb3-c3e0f9974ce6" width="220" alt="Login Screen">
  <img src="https://github.com/user-attachments/assets/943eb44d-6a57-493e-9182-36cca4923c14" width="220" alt="Keyboard UI Polish">
</p>

### 2. Real-Time Messaging (Sender vs Receiver)
<p align="center">
  <img src="https://github.com/user-attachments/assets/7c7829b3-6d09-48ea-8fa0-8776fd251701" width="250" alt="Sender View">
  <img src="https://github.com/user-attachments/assets/ee17603f-2e81-47d5-9b63-b6c99dc0d83a" width="250" alt="Receiver View">
</p>
<p align="center">
  <em>Above: Demonstration of real-time data sync. Left is 'Me', Right is the 'Receiver'. UI adapts dynamically based on the current user.</em>
</p>

## 🛠 Tech Stack & Libraries

* **Language:** Swift 5
* **Interface:** UIKit (Programmatic & Storyboard)
* **Backend & Auth:** Firebase (Firestore & Auth)
* **Dependency Manager:** CocoaPods
* **3rd Party Libraries:**
    * `IQKeyboardManagerSwift`: Handles keyboard interactions and screen sliding automatically.
    * `CLTypingLabel`: Adds a typewriter animation effect to the title screen.
    * `Firebase/Auth`: Manages secure user authentication.
    * `Firebase/Firestore`: Powers the real-time database functionality.

## ✨ Features

* 🔐 **Secure Authentication:** Sign Up and Log In capabilities using Firebase Auth.
* 💬 **Real-Time Messaging:** Instant data transmission using Cloud Firestore.
* 🎨 **Custom UI:** Custom `MessageBubble` design and dynamic bubble coloring based on the sender.
* ⌨️ **Smart Keyboard Handling:** Smooth user experience with automatic screen adjustment when typing.

## 🚀 Installation (How to Run)

To run this project on your local machine, follow these steps:

1.  Clone the repository:
    ```bash
    git clone https://github.com/Dev-MuTTiNeeR/Flash-Chat-iOS13.git
    ```
2.  Navigate to the project directory and install Pods:
    ```bash
    cd Flash-Chat-iOS13
    pod install
    ```
3.  Open the `.xcworkspace` file (not the .xcodeproj).
4.  **Important Note:** For security reasons, the `GoogleService-Info.plist` file is not included in the repository. To run the app, you must create your own Firebase project, download your specific `GoogleService-Info.plist`, and place it inside the `Flash Chat iOS13` folder.

## 👨‍💻 Developer

**Cem** - [My GitHub Profile](https://github.com/Dev-MuTTiNeeR)

---
*This project was built and customized as part of Angela Yu's iOS Development Bootcamp.*
