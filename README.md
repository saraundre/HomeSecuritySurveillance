# HomeSecuritySurveillance

## Overview

This GitHub repository is dedicated to the Home Security Surveillance project, which is a part of the Software Engineering Course in the 3rd Year, 2nd Semester. The project's design topic is centered around Home Security Surveillance and is developed in collaboration with China Telecom Guangdong Company in 2022.

## Background

In contemporary times, the safety of households is becoming increasingly important due to various safety hazards such as short circuits, fires, gas leaks, and unauthorized intrusions. This project explores innovative methods for enhancing home security through video feeds from installed home cameras. It combines video technology with advanced AI analysis and training algorithms to address the challenge of AI-based home safety monitoring.

The system's primary objectives include:

1. **Smoke and Flame Detection**: The system can detect the presence of smoke and flames, triggering alarms in case of fire hazards.

2. **Intrusion Detection**: It is capable of identifying unauthorized individuals entering specific areas within a specified time frame and raising alarms when strangers intrude.

## References

- The project makes use of video processing and recognition algorithms with AI.

## Hardware Requirements

- PC 1: 
  - CPU: 2 cores
  - RAM: 16GB
  - Storage: 100GB hard drive
  - Camera

## Data Requirements

No specific data requirements are necessary for this project.

## Test Environment

The system is designed to operate in a network-connected environment.

## Home Surveillance Security System Setup

Follow these steps to set up the Home Surveillance Security System:

1. **Clone Yolov5 Repository**: 
   - Clone the Yolov5 repository by running the following command:
     ```bash
     git clone https://github.com/ultralytics/yolov5  # clone
     cd yolov5
     ```

2. **Telegram Bot API Setup**:
   - In the Telegram app, locate the Bot Father API, register a new bot, and save the generated token.

3. **Configure Telegram API**:
   - Copy the following URL and replace `<TOKEN>` with the generated token:
     ```
     https://api.telegram.org/bot<TOKEN>/getUpdates
     ```

4. **Move Weight Files**:
   - Move the "best.pt" weights to the yolov5 folder.

5. **Create "detected" Folder**:
   - Create a folder named "detected" within the project directory.

6. **Open Notebook and Specify Path**:
   - Open the notebook and specify the path to the weight file.

7. **Run the Script**:
   - Execute the script to start the home surveillance security system.

---

**Note**: For any questions, issues, or feedback, please don't hesitate to reach out or open an issue in this repository.
