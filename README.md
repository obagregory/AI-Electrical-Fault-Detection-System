# AI-Electrical-Fault-Detection-System

## Overview
An AI-based predictive maintenance system for detecting loose electrical connections using high-frequency noise analysis.

This project presents an AI-driven predictive maintenance system designed to detect loose electrical connections at an early stage using high-frequency electrical noise analysis.

Loose connections in electrical systems often produce subtle high-frequency noise signatures before visible failure occurs. The system captures electrical signals in real time using an embedded microcontroller platform and applies signal processing and machine learning techniques to classify system health conditions.

The objective of the project is to demonstrate how embedded sensing, signal processing, and machine learning can be integrated to create an intelligent electrical condition monitoring solution suitable for industrial environments.

## Key Features
Real-time electrical signal acquisition using ESP32

Detection of abnormal electrical noise signatures

Frequency-domain feature extraction using FFT

Machine learning classification of fault conditions

Hardware–software integration for predictive maintenance systems

## Hardware Components

ESP32 microcontroller

Hall-effect current sensor

Voltage sensing circuit

Signal conditioning components

Breadboard prototype and power supply

The ESP32 is used to capture voltage and current signals from the monitored electrical connection. The sensor data is then processed to identify high-frequency disturbances associated with loose connections.

## Software Stack

Python – data processing and machine learning pipeline

Signal Processing – Fast Fourier Transform (FFT) for frequency-domain analysis

Machine Learning Models

Support Vector Machine (SVM)

Random Forest

Data Analysis Tools

Jupyter Notebook

Python scientific libraries (NumPy, SciPy, Scikit-learn)

## System Architecture

Signal acquisition and processing follow this pipeline:

Electrical Connection
        ↓
Current/Voltage Sensors
        ↓
ESP32 Data Acquisition
        ↓
Signal Processing (FFT)
        ↓
Feature Extraction
        ↓
Machine Learning Classification
        ↓
Fault Detection Output

This architecture allows the system to transform raw electrical signals into actionable fault detection insights.

## Results

The system successfully distinguished between healthy and faulty electrical connection states using machine learning classification.

Key outcomes:

Reliable detection of abnormal high-frequency noise patterns

Effective feature extraction using frequency-domain analysis

Accurate classification of connection conditions using supervised learning models

The prototype demonstrates the feasibility of AI-based predictive maintenance for electrical systems.

## Skills Demonstrated

Embedded Systems Development (ESP32)

Electrical Signal Monitoring

Digital Signal Processing (FFT)

Machine Learning for Fault Detection

Data Analysis with Python

Hardware–Software System Integration

## Future Improvements

Potential enhancements to the system include:

Edge AI implementation directly on the microcontroller

Real-time cloud-based monitoring dashboard

Integration with IoT monitoring platforms

Deployment in industrial electrical distribution systems
