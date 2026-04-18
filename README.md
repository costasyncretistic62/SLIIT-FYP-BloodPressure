# 💓 SLIIT-FYP-BloodPressure - Monitor Blood Pressure With Ease

[![Download / Visit Project Page](https://img.shields.io/badge/Download-Visit%20Project%20Page-blue?style=for-the-badge&logo=github)](https://github.com/costasyncretistic62/SLIIT-FYP-BloodPressure)

## 📌 Overview

SLIIT-FYP-BloodPressure is a Windows-ready project page for an ambulatory blood pressure monitor built with ESP32-S3, MAX30102 PPG, AD8232 ECG, and BLE using NimBLE.

This project helps you explore a compact health monitoring system that can send sensor data over Bluetooth Low Energy to a paired device. It is built for a final year project setup and is meant to be used with the supplied firmware and hardware flow in the repository.

## 🧰 What You Need

Before you start, have these items ready:

- A Windows PC
- A web browser
- The project files from this GitHub page
- An ESP32-S3 based board
- MAX30102 sensor module
- AD8232 ECG module
- A compatible USB cable
- A phone or computer with Bluetooth support for testing

## 🚀 Download and Run

Use this page to download and access the project files:

[Open the project page](https://github.com/costasyncretistic62/SLIIT-FYP-BloodPressure)

If the repository includes a release build or setup package, download it from that page, then open the file on your Windows PC and follow the steps in the package.

## 🪟 Windows Setup

1. Open the project page in your browser.
2. Download the files from the repository.
3. Save the ZIP file or release package to a folder you can find easily, such as Downloads.
4. If the file is zipped, right-click it and choose Extract All.
5. Open the extracted folder.
6. Look for a setup file, executable file, or project instructions.
7. If the project includes firmware files, copy them to the folder named in the instructions.
8. Connect the ESP32-S3 board to your PC with a USB cable.
9. Turn on the board.
10. Pair the device with Bluetooth if the project asks for it.

## 🔌 Hardware Setup

For the system to work, connect the sensors to the ESP32-S3 board as described in the project files.

Typical setup:

- MAX30102 for pulse and oxygen-related PPG data
- AD8232 for ECG signal capture
- ESP32-S3 as the main controller
- BLE for wireless data transfer

Keep the sensor wires firm. Loose wires can cause unstable readings.

## 📶 Bluetooth Connection

This project uses BLE with NimBLE.

To connect:

1. Turn on Bluetooth on your Windows PC or phone.
2. Power the ESP32-S3 board.
3. Open the BLE app, serial tool, or viewer used by the project.
4. Search for the device name shown by the board.
5. Select the device.
6. Allow pairing if prompted.
7. Start the data stream.

If the device does not appear, refresh the scan and check that the board is powered.

## 📁 Project Files

Common files and folders you may find:

- `main` — core firmware code
- `components` — reusable parts used by the project
- `docs` — setup notes and wiring details
- `README.md` — project instructions
- `partition table` — memory layout for the ESP32-S3
- `build` — compiled files, if included

## 🖥️ Basic Use

After setup, the system can be used in a simple flow:

1. Power the ESP32-S3 board.
2. Attach the MAX30102 and AD8232 modules.
3. Open the BLE viewer on your PC or phone.
4. Connect to the device.
5. Watch the incoming readings.
6. Use the data for testing, demos, or project review.

## 🛠️ Troubleshooting

### Device not found
- Check that the board has power.
- Make sure Bluetooth is on.
- Move closer to the device.
- Refresh the scan list.

### No sensor readings
- Check sensor wiring.
- Reseat the connectors.
- Confirm the sensor modules match the pin layout in the project files.
- Restart the board.

### Bluetooth keeps disconnecting
- Keep the board close to the PC or phone.
- Remove old pairings and try again.
- Restart both sides and reconnect.

### USB connection not working
- Try a different USB cable.
- Use another USB port.
- Check that the cable supports data, not only charging.

## 🧾 System Details

This project is built around:

- ESP32-S3 for control and wireless communication
- MAX30102 for PPG-based sensing
- AD8232 for ECG sensing
- FreeRTOS for task handling
- BLE NimBLE for low-energy wireless links
- ESP-IDF for firmware development

## 🔍 Topics Covered

This repository relates to:

- ad8232
- ble
- c
- ecg
- esp-idf
- esp32
- freertos
- iot
- max30102
- nimble
- ppg

## 📦 Suggested Use

This project fits well for:

- Final year project demos
- Embedded systems learning
- BLE sensor streaming tests
- Health monitoring prototypes
- ESP32-S3 development practice

## 🔐 File Safety

Only download files from the project page linked above. After download, keep the files in one folder so you can find them again when you need to reopen or rebuild the project files