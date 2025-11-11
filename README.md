# ADS502_FinalProject
### By Mason Delan & Shesma Jaganathan

## 1. Project Overview

### Problem Statement
This project explores how accurately the number of people in a room can be predicted using environmental sensor data.  
The goal is to estimate occupancy levels based on signals such as temperature, CO2, light, and sound intensity.

### Background and Motivation
Understanding room occupancy is valuable for energy efficiency, HVAC automation, and smart-building management.  
Rather than using cameras or intrusive tracking, this project focuses on data from non-invasive IoT sensors to create a privacy-friendly approach to detecting when and how many people are present.

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
