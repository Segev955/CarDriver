# CarDriver Project

The **CarDriver Project** is a comprehensive solution for detecting vehicle theft by analyzing driver behavior in real-time using OBD-II data and GPS information.

## Repositories

- [CarDriver-Android](https://github.com/Segev955/CarDriver-Android): Android app for collecting OBD-II data and displaying notifications.
- [car-driver](https://github.com/Segev955/car-driver): Node.js backend for data processing, machine learning integration, and Firebase handling.
- [OBDII-Data](https://github.com/Segev955/OBDII-Data): Python scripts for processing OBD-II and GPS data, and machine learning model integration.

## Project Workflow

1. **Data Collection**:
   - OBD-II data is collected by the Android app and sent to Firebase or directly to the backend.

2. **Data Processing**:
   - The backend retrieves the data from Firebase and processes it using the machine learning models defined in the **OBDII-Data** repository.

3. **Driver Identification & Theft Detection**:
   - The backend predicts the driver or detects possible theft based on driving patterns.
   - Results are sent back to Firebase or directly to the Android app.

4. **Notifications**:
   - Real-time notifications are sent to the user via Firebase Cloud Messaging (FCM) when unusual activity is detected.

## How to Set Up

1. Clone the repositories:
    ```bash
    git clone https://github.com/Segev955/CarDriver-Android.git
    git clone https://github.com/Segev955/car-driver.git
    git clone https://github.com/Segev955/OBDII-Data.git
    ```

2. Set up Firebase for real-time data storage.

3. Run the backend and Android app to start the system.
