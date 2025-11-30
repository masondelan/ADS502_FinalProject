# ADS502_FinalProject
### By Mason Delan & Shesma Jaganathan

## 1. Project Overview

### Problem Statement
This project focuses on predicting room occupancy using environmental IoT sensor data. Instead of estimating the exact number of people present, the objective is to classify whether a room is occupied or unoccupied. This approach is more suitable for the dataset, which contains a much larger proportion of unoccupied readings compared to occupied ones.

### Background and Motivation

Accurate occupancy detection supports energy-efficient building automation, HVAC optimization, and smart-building management. Because the method relies on non-invasive sensor measurements—such as temperature, CO₂ levels, sound intensity, light readings, and PIR motion—it avoids the privacy concerns associated with camera-based monitoring. By leveraging these environmental signals, this project develops machine learning models that provide a sensor-driven, privacy-friendly way to determine room occupancy.

---

## 2. Dataset Description

The dataset used in this project is the **Room Occupancy Estimation** dataset from the UCI Machine Learning Repository:  
[https://archive.ics.uci.edu/dataset/864/room+occupancy+estimation](https://archive.ics.uci.edu/dataset/864/room+occupancy+estimation)

### Overview
- Collected in a 6 m × 4.6 m room over four days, without HVAC running.  
- Contains **10,129 observations** and **18 sensor-based features**.  
- Measurements include **temperature**, **humidity**, **CO2**, **light**, **sound**, and **passive infrared (PIR) motion**.  
- The target variable indicates the **number of occupants (0–3)**.  
- The dataset is complete, with **no missing values**.  

This dataset was chosen because it’s compact, well-structured, and directly supports real-world applications in smart environments and energy management.
