# SIH 1710 – Enhancing Navigation for Railway Station Facilities and Locations
## Date: 29.05.2026
## Name: Tarunika D
## Register no: 212223040227
## Problem Statement

Railway stations are often large and complex environments containing multiple facilities such as platforms, ticket counters, waiting halls, food courts, restrooms, elevators, escalators, and emergency exits. Passengers frequently face difficulties locating these facilities, especially in unfamiliar stations.

The proposed solution is a smart navigation system that provides real-time indoor navigation, accessibility support, and facility discovery through mobile applications, digital kiosks, and voice-guided assistance.

---

# System Architecture Diagram
<img width="1536" height="1024" alt="ChatGPT Image May 29, 2026, 02_07_11 PM" src="https://github.com/user-attachments/assets/0213ef97-ac28-468d-8f33-0627072b4dab" />

## Architecture Overview

The system follows a layered architecture consisting of:

### 1. Presentation Layer
Provides user interaction through:

- Mobile Application
- Digital Kiosks
- Web Portal
- Voice Assistant Interface

### 2. Application Layer
Responsible for core business logic:

- User Management Service
- Navigation Engine
- Indoor Mapping Service
- Search & Discovery Service
- Notification Service
- Feedback & Support Service

### 3. API Gateway
Acts as a centralized entry point for all client requests.

Functions:
- Authentication
- Authorization
- Request Routing
- Rate Limiting

### 4. Backend Services Layer

Includes:

- Content Management Service
- Real-Time Update Service
- Analytics Service
- Accessibility Service
- Route Guidance Service
- AI/ML Recommendation Service

### 5. Data Layer

Stores and manages:

- User Data
- Station Layout Information
- Facility Information
- Navigation Graph Data
- Real-Time Updates
- Analytics Reports

### 6. Infrastructure Layer

Supports deployment and scalability through:

- Cloud Servers
- Load Balancers
- Docker Containers
- CDN
- Monitoring & Logging
- Backup & Recovery
- Security Services

### External Integrations

The system integrates with:

- Railway Information Systems
- Ticket Booking Systems
- Public Announcement Systems
- Payment Gateways

---

# Use Case Diagram
<img width="1402" height="1122" alt="ChatGPT Image May 29, 2026, 02_05_36 PM" src="https://github.com/user-attachments/assets/400ddd4d-0b29-4eeb-a7f7-0353dbdb2c47" />

## Actors

### Passenger
Uses the application to locate facilities and navigate through the station.

### Visually Impaired Passenger
Uses voice-guided navigation and accessibility features.

### Senior Citizen / Differently-Abled Passenger
Requests accessible routes with elevators and ramps.

### Station Administrator
Manages maps, facilities, and station information.

### Railway Services System
Provides train schedules, platform updates, and announcements.

### Digital Kiosk
Acts as an alternative navigation interface inside stations.

---

## Use Cases

### Passenger

- Open Application
- Search Destination
- View 3D Station Map
- Get Navigation Directions
- View Nearby Facilities
- Receive Notifications
- Set User Preferences

### Visually Impaired Passenger

- Voice-Guided Navigation
- Accessibility Assistance

### Senior Citizen / Differently-Abled Passenger

- Request Accessible Route
- Emergency SOS / Help Request

### Station Administrator

- Manage Station Maps
- Update Facility Information
- Monitor Navigation Services

### Railway Services

- Provide Real-Time Updates
- Platform Change Notifications
- Schedule Integration

---

# Working Flow

```text
User Opens App
      ↓
Current Location Detected
      ↓
Destination Selected
      ↓
Navigation Engine Calculates Route
      ↓
3D Map & Voice Guidance Generated
      ↓
Real-Time Updates Monitored
      ↓
Passenger Reaches Destination
