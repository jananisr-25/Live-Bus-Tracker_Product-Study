# Live-Bus-Tracker_Product-Study

A mobile-first live bus tracking solution designed to reduce uncertainty and waiting time for campus commuters.

## Problem

Students often wait 15–30 minutes for campus buses without knowing their current location or arrival time. Static timetables are frequently unreliable, leading to frustration and inefficient travel planning.
Pl note that this prototype & deck was developed when there was no concrete app for tracking insti buses.

## Solution

Live Bus Tracker provides real-time visibility of active buses through an interactive institute map.

Users can:

* View all active buses on a live map
* Track bus movement in real time
* View route information for each bus
* Search stops and routes
* Check estimated arrival times (ETA)
* Discover nearby bus stops

The solution is designed to be lightweight, accessible, and easy to use without requiring complex setup.

---

## Key Features

### Core MVP

* Live map with active buses
* Real-time location updates
* Route information popups
* Mobile-first interface

### Future Enhancements

* Smart ETA prediction
* Push notifications
* Route analytics
* Crowding estimation

---

## User Flow

### Driver

1. Login
2. Select route
3. Start location sharing
4. Location sent continuously to backend

### User

1. Open app
2. View live map
3. Track buses
4. Search routes and stops
5. View ETAs

---

## Technical Architecture

Driver Interface
↓
GPS Location
↓
Firebase Realtime Database
↓
User Interface
↓
Live Map Updates

### Proposed Tech Stack

| Component         | Technology                 |
| ----------------- | -------------------------- |
| Frontend          | Flutter                    |
| Backend           | Firebase Realtime Database |
| Maps              | Google Maps API            |
| Location Services | GPS                        |
| Hosting           | Firebase Hosting           |

---

## Design Prototype

### Figma Prototype

https://www.figma.com/design/q4XKK7TEwdsaGJljRnDRJt/Live-bus-tracker-prototype?node-id=0-1&t=R7xik5yxbQrVCxmD-1

### Screens

<img width="880" height="317" alt="image" src="https://github.com/user-attachments/assets/bf610a4a-c45a-4547-88ec-ce44d9467523" />
<img width="897" height="526" alt="image" src="https://github.com/user-attachments/assets/1bb37b6a-1321-4603-a3a8-e6d61d089b44" />


---

## Impact

The solution aims to:

* Reduce perceived waiting time by 75%
* Improve commuter confidence
* Eliminate uncertainty around bus arrivals
* Provide a simple and intuitive tracking experience

---

