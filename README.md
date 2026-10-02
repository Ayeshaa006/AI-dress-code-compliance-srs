#  AI Dress Code Compliance System

## Overview

This repository contains the Software Requirements Specification (SRS) for an AI-driven Dress Code Compliance System. The proposed system is designed to use Computer Vision and Deep Learning techniques to monitor workplace dress code compliance through CCTV video streams.

The system is intended to detect mandatory clothing items such as formal shirts, ties, and ID cards and provide visual compliance indicators. The proposed solution focuses on local processing to support privacy and aims to generate compliance records and reports for HR management.

##  Proposed Technologies

* **Python** — Core programming language
* **YOLOv8** — Object detection
* **OpenCV** — Real-time video and frame processing
* **PyTorch** — Deep Learning framework
* **Pandas** — Data analysis and report generation
* **Roboflow** — Dataset annotation and management

##  Proposed System Workflow

1. **Camera Input:** The system receives video from a CCTV or USB camera.
2. **Object Detection:** Video frames are analyzed using a YOLOv8-based object detection model.
3. **Compliance Verification:** Detected clothing items are compared with predefined dress code requirements.
4. **Visual Feedback:** The system provides visual indicators for compliant and non-compliant cases.
5. **Violation Logging:** Non-compliant events can be recorded with relevant timestamps and missing-item information.
6. **Report Generation:** Compliance data can be organized into summary reports for HR management.

##  Proposed Features

* Real-time dress code monitoring
* Detection of multiple clothing and identification items
* Visual compliance indicators
* Violation logging
* Daily compliance reporting
* Local processing with a focus on privacy
* Modular software architecture

##  Project Documentation

The main file in this repository is the **Software Requirements Specification (SRS)** document. It describes the proposed system, its requirements, features, users, constraints, and overall functionality.

##  Project Purpose

The purpose of this Software Engineering project is to document the requirements and proposed functionality of an AI-based Dress Code Compliance System. The project demonstrates how Computer Vision and Deep Learning can be applied to a real-world workplace monitoring problem.

## Author

**Ayesha Manzoor**
BSAI Student
Superior University, Lahore

**Project Advisor:** Syed Zeeshan Hussain
