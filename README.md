# ChitChat - Mobile Messaging App

ChitChat is a mobile application built using Flutter and Firebase. This guide will help you set up the development environment, configure Firebase, and add virtual devices to run the application.

## Useful links

- [Flutter](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Android Studio](https://developer.android.com/studio)

## Setup Guide

### Step 1: Install Flutter and Dart Plugins in Visual Studio Code
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar or by pressing Ctrl+Shift+X.
3. Search for Flutter and click Install.
4. Similarly, search for Dart and click Install.

### Step 2: Configure Flutter in Visual Studio Code
1. Open the terminal in Visual Studio Code (Ctrl+`` or via the Terminal > New Terminal` menu).
2. Verify the installation by running the following command:   flutter doctor

### Step 3: Clone the Source Code Repository
1. Open your terminal.
2. Clone the application repository using the following command:  git clone https://github.com/dennysapopescu/PopescuDennysa_Licenta.git
3. Navigate into the project folder.

### Step 4: Install Dependencies
Once Flutter and Dart are correctly installed and configured, open the terminal in the project root directory and run:  flutter pub get

### Firebase Configuration
1. Manual Firebase setup is not required, as the application is already pre-configured to connect to an existing Firebase project.
2. You only need to ensure that the Firebase configuration files are in the correct place. Specifically, verify that the google-services.json file is located in the android/app directory.

### Adding Virtual Devices using Android Studio
1. Open Android Studio.
2. Navigate to the AVD Manager (Device Manager) from the Tools menu or by clicking its respective icon.
3. Click on Create Virtual Device.
4. Select a hardware device definition and click Next.
5. Choose a system image (OS version) and click Next.
6. Verify the configuration details and click Finish.
7. Launch the virtual device from the manager list.

### Step 5: Target the Virtual Device in Visual Studio Code
1. Ensure your virtual device (emulator) is actively running.
2. In Visual Studio Code, open the Command Palette (Ctrl+Shift+P).
3. Type and select: Flutter: Select Device.
4. Choose your running virtual device from the drop-down list.

### Step 6: Running the Application
1. Open the Flutter project folder in Visual Studio Code.
2. Select your target device from the bottom status bar, then navigate to the Run and Debug icon in the Activity Bar to start the app.
   
### Key Reminders:
1. File Location: Always double-check that the google-services.json file is precisely located inside the android/app folder.
2. Troubleshooting: Run flutter doctor at any time to diagnose environment issues and follow its guided prompts to resolve them.
