# Distributed ICU Patient Monitoring System

## 1. Project Overview

The **Distributed ICU Patient Monitoring System** is an embedded system designed to continuously monitor the vital health parameters of multiple ICU patients from a centralized monitoring station.

The system collects patient health information such as heart rate, body temperature, and oxygen saturation (SpO2) using sensors. The collected data is processed by a microcontroller and transmitted to a central monitoring unit, allowing healthcare professionals to monitor multiple patients simultaneously.

The system generates alerts whenever monitored parameters cross predefined safety thresholds, helping medical staff respond quickly to critical situations.

## 2. Objectives

- Monitor multiple ICU patients simultaneously.
- Measure vital health parameters in real time.
- Collect and transmit patient data to a central monitoring station.
- Detect abnormal health conditions.
- Generate alerts during critical situations.
- Improve patient monitoring and healthcare efficiency.

## 3. Hardware Requirements

| Component | Description |
|---|---|
| Microcontroller | Processes patient sensor data |
| Heart Rate Sensor | Measures heart rate |
| Temperature Sensor | Measures body temperature |
| SpO2 Sensor | Measures blood oxygen saturation |
| LCD Display | Displays patient readings |
| Communication Module | Transfers data between patient units and central station |
| Buzzer | Provides an emergency alert |
| Power Supply | Provides power to the system |

## 4. Software Requirements

- Embedded C Programming
- Keil µVision IDE
- Flash Magic
- Proteus (if used for simulation)
- Required microcontroller development environment

## 5. System Architecture

The system consists of two main sections:

### A. Patient Monitoring Unit

- Collects patient health parameters using sensors.
- Processes the sensor readings through a microcontroller.
- Transmits patient information to the central monitoring station.
- Detects abnormal readings based on predefined thresholds.

### B. Central Monitoring Unit

- Receives information from multiple patient monitoring units.
- Displays patient health parameters.
- Identifies abnormal patient conditions.
- Generates alerts to notify medical staff.

## 6. Working Principle

1. The system initializes the microcontroller and connected sensors.
2. Sensors collect patient health parameters.
3. The microcontroller reads and processes the sensor values.
4. Patient data is transmitted to the central monitoring unit through a communication interface.
5. The central unit receives data from multiple patient monitoring units.
6. Patient readings are displayed for medical staff.
7. If any parameter exceeds its predefined safety limit, an alert is generated.
8. The monitoring process continues continuously.

## 7. System Features

- Multiple patient monitoring.
- Real-time health parameter monitoring.
- Heart rate measurement.
- Body temperature monitoring.
- SpO2 monitoring.
- Centralized patient data collection.
- Automatic abnormal-condition alerts.
- Improved ICU monitoring efficiency.

## 8. Applications

- Intensive Care Units (ICU).
- Hospitals and healthcare centers.
- Emergency care units.
- Critical patient monitoring.
- Remote healthcare monitoring systems.

## 9. Advantages

- Enables simultaneous monitoring of multiple patients.
- Reduces the workload of medical staff.
- Provides continuous patient health information.
- Helps identify abnormal health conditions quickly.
- Improves monitoring efficiency.
- Supports centralized patient management.

## 10. Future Enhancements

- IoT-based remote patient monitoring.
- Cloud-based patient data storage.
- Mobile application integration.
- SMS and email emergency notifications.
- Artificial Intelligence-based health analysis.
- Historical patient data visualization.
- Wireless communication between patient units and the central station.

## 11. Conclusion

The Distributed ICU Patient Monitoring System provides an embedded solution for monitoring multiple patients from a centralized monitoring station. By collecting vital health parameters and generating alerts during abnormal conditions, the system helps healthcare professionals observe patient conditions more efficiently and respond to potential emergencies.

**Note:** This project is intended as an educational prototype and should not replace certified medical monitoring equipment or clinical judgment.

---

## Project Information

| Category | Details |
|---|---|
| Project Name | Distributed ICU Patient Monitoring System |
| Domain | Embedded Systems |
| Programming Language | Embedded C |
| Platform | Microcontroller-based System |
| Application | Healthcare and Patient Monitoring |
