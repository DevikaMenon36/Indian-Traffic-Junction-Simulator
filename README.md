# Indian-Traffic-Junction-Simulator

## Overview
The **Traffic Management System Using Unity3D** is an interactive simulation designed to manage urban traffic dynamically. The system adjusts traffic signal timings in real-time based on vehicle density in each lane, reducing congestion and improving overall traffic flow. The simulation also incorporates realistic driving behaviors inspired by Indian traffic conditions, making it a culturally relevant and practical solution for urban mobility challenges.

## Features
- **Dynamic Signal Adjustment**: Automatically adjusts traffic signals based on real-time lane congestion.
- **Manual Signal Control**: Enables priority control for high-priority vehicles like ambulances or police cars.
- **Realistic Driving Simulation**: Vehicles mimic real-world behaviors, such as assertive lane changes and collision avoidance.
- **Data-Driven Approach**: Uses CSV files to store and analyze vehicle counts for traffic signal management.
- **Scalability**: Designed for single intersections with potential for multi-intersection expansions.
- **Flexible Applications**: Useful for urban planning, autonomous vehicle testing, driver training, and game development.

## Technologies Used
- **Unity3D**: For creating the simulation environment.
- **Python**: For data generation, randomization, and analysis.
- **C#**: For real-time traffic signal control and vehicle behavior management.

## How it works
- Vehicle Count Generation: Random vehicle counts are generated for each lane and stored in text files.
- Data Sorting and Analysis: The data is read, sorted, and saved to a CSV file for signal prioritization.
- Signal Adjustment: Traffic signals dynamically adjust based on vehicle density.
- Manual Override: Users can manually control signals during emergencies or high-priority scenarios.
- Reset and Loop: The system resets and generates new traffic data for the next cycle.

## Demo Video
https://github.com/user-attachments/assets/50d77bfa-7b6b-4c7a-87c3-ea8a10eb6306

