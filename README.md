📌 Project Overview
This project introduces an AI-driven Smart Traffic Management System designed to revolutionize urban mobility. 
By leveraging YOLOv8 for real-time vehicle detection, DeepSORT for tracking, and Google Maps API for route optimization, the system enables intelligent traffic signal control, emergency vehicle prioritization, and data-driven traffic analytics.
The framework minimizes dependence on manual traffic control and optimizes traffic flow while ensuring faster response times during emergencies.

✨ Key Features
Real-Time Vehicle Detection & Classification - Uses YOLOv8 and DeepSORT to detect and track Light Motor Vehicles (LMVs), Heavy Motor Vehicles (HMVs), and emergency vehicles.
Adaptive Traffic Signal Control - Dynamically modifies signal timings based on traffic density and vehicle composition to reduce congestion.
Emergency Vehicle Prioritization - Automatically detects ambulances, fire trucks, and police vehicles, granting them priority by switching signals to green.
Scalable Smart City Integration - Can be deployed across multiple intersections with centralized dashboards for monitoring, analytics, and coordinated signal control.
Environmental Benefits - Reduces idle times, fuel consumption, and carbon emissions, contributing to sustainable urban infrastructure.


🛠️ Tech Stack
Computer Vision & AI: YOLOv8, DeepSORT
Programming Language: Python
APIs & Tools: Google Maps API, OpenCV
Dashboard & Visualization: Streamlit / Flask / Custom dashboards
Hardware Requirements: Surveillance cameras at intersections, GPU-enabled system for real-time inference


📂 Project Workflow
Capture live video feed from strategically placed road cameras
Detect and classify vehicles using YOLOv8
Track vehicles across frames with DeepSORT (unique IDs assigned)
Generate dynamic statistics: vehicle count, lane density, average speed
Apply adaptive traffic signal control logic
Prioritize emergency vehicles through automatic signal override
Provide real-time insights via dashboards for traffic operators


🚑 Use Cases
Faster ambulance and emergency service response times
Reduced congestion in high-density urban areas
Data-driven insights for city planners and policymakers
Sustainable mobility solutions with lower fuel usage and emissions


📊 Future Scope
Integration with IoT sensors for vehicle-to-infrastructure communication
AI-driven predictive traffic modeling for congestion avoidance
Expansion to multi-city deployments with centralized cloud systems
Voice-enabled navigation system for ambulance drivers.








