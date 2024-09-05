
# **ESP32 Find My Device Tracker**

This project aims to build a low-cost tracking device using an ESP32 module integrated with the "Find My" network. The device helps track objects in real-time using Bluetooth Low Energy (BLE) communication.

## **Team Members**

- **Vo Tuan Kiet**
- **Nguyen Duc Hung**
- **Dang Tuan Anh**
- **Tran Chi Thanh**
- **Hoang Thi Tuyet My**

## **Project Overview**

The ESP32 Find My Device Tracker is designed to help locate and track objects through Apple's "Find My" network using BLE signals. This project showcases the ability to develop a small-scale tracking device that integrates with widely used tracking systems, making it both practical and scalable.

## **Features**

- **Bluetooth Low Energy (BLE):** Utilizes BLE for communication between the ESP32 and nearby devices on the Find My network.
- **Low Power Consumption:** Optimized for long battery life by minimizing power usage when idle.
- **Customizable:** Can be modified to track various types of objects, such as personal belongings, bikes, or pets.
- **Open Source:** Code is available for customization and improvements.

## **Components Used**

- **ESP32-WROOM-32:** The core microcontroller used for BLE communication.
- **Lithium Polymer (LiPo) Battery:** Powers the ESP32.
- **BLE Library for ESP32:** Enables the use of Bluetooth Low Energy on the ESP32 module.

## **How It Works**

1. **Initialization:** The ESP32 starts in BLE advertising mode, broadcasting a signal that nearby devices can detect.
2. **Device Detection:** Devices on the Find My network detect the BLE signal, relaying the location data back to the Find My app.
3. **Tracking:** The user can view the tracked device's location through the Find My app.

## **Installation & Setup**

1. Clone this repository to your local machine:
    git clone https://github.com/......git

2. Open the project in Arduino IDE or PlatformIO.
3. Install the necessary libraries for ESP32 BLE:
    - ESP32 BLE Arduino Library
4. Configure the BLE device name and UUID in the source code.
5. Flash the ESP32 with the modified firmware using a USB cable.
6. Connect the battery to the ESP32 module.

## **Usage**

Once set up, place the ESP32 tracker on the object you want to monitor. It will start broadcasting its BLE signal, allowing the object to be tracked using the Find My network.

## **Future Development**

- Integration with other tracking networks.
- Implementing additional sensors (e.g., GPS) for enhanced tracking accuracy.
- Improving battery optimization techniques.

## **Contributors**

- Vo Tuan Kiet
- Nguyen Duc Hung
- Dang Tuan Anh
- Tran Chi Thanh
- Hoang Thi Tuyet My