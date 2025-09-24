# blueguard-project
Coastal Smart Buoy Disaster Communication System

Description
A solar-powered smart buoy network using ESP32 and LoRa mesh for real-time emergency alerts and rescue coordination in coastal disaster zones. Provides reliable communication without mobile towers, with GPS tracking, SOS buttons, floating shelters, and cloud integration using Microsoft Azure IoT.

Problem Statement
Coastal regions face frequent disasters like cyclones and floods, where communication infrastructure fails, leaving fishermen, tourists, and rescue teams without real-time alerts or coordination.

Solution Overview
Deploy solar-powered smart buoys that form a LoRa mesh network, enabling offline communication. Each buoy has GPS, sensors, an SOS button, and floating shelters. Gateways on shore connect to cloud dashboards for monitoring and alerting rescue teams efficiently.

Features
Solar-powered autonomous buoys with ESP32 microcontrollers

LoRa mesh communication between buoys

GPS location tracking and SOS emergency buttons

Floating shelter trigger with life-saving supplies

Gateway systems forwarding alerts to local dashboards and cloud

Cloud platform with Azure IoT Hub integration for data analysis

Real-time disaster alert system for coastal communities

System Architecture
Buoy Units (hardware and firmware)

LoRa Mesh Network (communication layer)

Gateway Layer (LoRa-to-IP servers)

Cloud Integration (Azure IoT Hub, Maps, Functions)

User Interfaces (mobile, handheld devices for rescue teams)

Installation / Setup
Instructions to deploy buoy hardware, set up LoRa gateways, build and upload ESP32 firmware, configure cloud services, and access dashboard.

Usage
How to operate the system during coastal emergencies, trigger SOS, monitor alerts, and communicate with rescue teams.
