Real-Time Cab Coordination & Tracking System

A professional, real-time web application designed to automate daily transit coordination for 80+ students and cab drivers. This system replaces fragmented WhatsApp communication with a live, role-based dashboard.

🚀 Live Demo

Link: [Paste your Netlify URL here]

🛠 Tech Stack

Frontend: HTML5, Tailwind CSS, JavaScript (ES6+)

Backend: Firebase Firestore (Real-time NoSQL)

Auth: Firebase Auth (Google OAuth 2.0)

Hosting: Netlify

Design: UML Modeling & Use Case Analysis

✨ Key Features

Real-Time Sync: Instant student count updates via Firestore listeners.

Role-Based Access Control (RBAC): Dedicated dashboards for Students and Drivers.

Hands-Free Safety: Event-driven audible alerts for drivers using Web Audio API.

Privacy-First: Student identities are masked from peers; visible only to the Driver.

📊 System Design (UML)

The project architecture was defined using UML Use Case Diagrams to map actor interactions and system boundaries.

Core Use Cases:

Student: Check-in at Hostel/College, View Driver Status.

Driver: Monitor Live Pickup List, Broadcast Alerts, View Map.

⚙️ Setup

Clone the repo.

Open index.html.

Add your Firebase config in the script tag.