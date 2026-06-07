# AI-Based Early Detection of Loose Electrical Connections

## Overview

This project presents an AI-powered predictive maintenance system designed to detect loose electrical connections before they develop into critical faults. The system combines embedded hardware, signal processing, and machine learning to identify abnormal electrical behaviour using high-frequency noise signatures.

## Features

* Real-time data acquisition using ESP32
* Electrical signal monitoring and analysis
* Feature extraction using RMS, Standard Deviation, and Peak Amplitude
* Machine learning-based fault classification
* Detection of Normal, Moderate Fault, Severe Fault, and Signal Loss conditions
* Visual and audible alerts using LEDs and buzzer
* MATLAB-based signal processing and model evaluation

## System Architecture

1. ESP32 acquires electrical signal data from the test circuit.
2. Signal data is transmitted for processing.
3. Features are extracted from the collected signals.
4. A machine learning model classifies the connection condition.
5. Fault status is displayed through LEDs, buzzer alerts, and monitoring outputs.

## Technologies Used

* ESP32
* MATLAB
* Python
* Machine Learning
* Signal Processing
* Embedded Systems
* Predictive Maintenance

## Results

The trained classification model achieved approximately **95.8% accuracy** in distinguishing between different connection conditions. Experimental testing demonstrated the system's ability to identify fault severity and provide early warning before critical failure occurs.

## Applications

* Predictive Maintenance
* Industrial Monitoring
* Electrical Safety Systems
* Smart Infrastructure
* IoT-Based Condition Monitoring

## Author

Gregory Oba
BEng (Hons) Electronics & Computer Engineering
University of Northampton
