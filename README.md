# Portable-ECG-Prototype
## 🔍 Overview
A portable Arduino-based ECG monitor

## 🛠️ Features
- Custom designed and 3D printed case and cover
- Heart rate detection with a Sparkfun AD8232 Heart Monitor and AUX electrode connections
- 128x64 OLED displaying ECG Signal, Heart Rate (BPM), and Threshold/Offset
- 2 potentiometers controlling signal offset for threshold and amplification
- External USB-C port for code updates

## 🎥 Demo
[Watch the video here](https://youtube.com/shorts/o9CAp9mGv5c)

## 📦 Bill of Materials
- PLA Filament (Grey)
- Arduino nano
- Prototype PCB
- AD8232 Heart Monitor
- 128x64 OLED
- 10 kohm potentiometers
- 9V battery and connector
- SPDT Switch
- Solder
- 3 pin auxillary connector with electrodes
- McMaster Carr 410 stainless steel No.6 Size 5/8" Long Pointed Screws for Plastic

## 🧠 How It Works
The Arduino powers the OLED, potentiometers, and the heart monitor sensor. The biosignal is picked up through the properly placed electrodes, filtered by the sensor, and sent to the Arduino as an analog signal. The Arduino also recieves analog signals from the potentiometers. It then creates a display that allows the user to view and adjust the signal display like an oscilloscope.

## 👨‍💻 My Role
I designed the PCB and CAD, wrote the firmware in C++, and handled data acquisition from the EMG sensors.

## 📜 License
MIT or open-hardware license info
