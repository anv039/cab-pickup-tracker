# 🚐 Cab Pickup Tracker: Real-Time Coordination System

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

A high-performance, real-time web application engineered to solve daily transit coordination challenges for 80+ students. This system replaces fragmented manual communication with a centralized, data-driven dashboard.

## 🚀 Live Demo
**Access the live application here:** [PASTE_YOUR_NETLIFY_URL_HERE]

---

## 🛠 Technical Architecture
* **Frontend:** Responsive SPA built with **HTML5** and **Tailwind CSS**, optimized for mobile-first utility.
* **Real-time Engine:** **Firebase Firestore** NoSQL database utilizing `onSnapshot` listeners for sub-second data synchronization.
* **Security & Auth:** **Google OAuth 2.0** integrated via Firebase Authentication for secure user entry.
* **Audio Logic:** **Web Audio API** for event-driven audible notifications, enhancing driver safety.
* **Deployment:** Continuous integration and delivery (CI/CD) managed via **Netlify**.

## ✨ Key Features & Technical Impact
* **Dynamic State Synchronization:** Real-time tracking of student check-ins at multiple waypoints without the need for manual page refreshes.
* **Role-Based Access Control (RBAC):** Engineered distinct data-views for Students and Drivers to ensure a tailored user experience and operational efficiency.
* **Privacy-First Engineering:** Implemented data-masking protocols that protect student identities from peers while providing the driver with an actionable, secure pickup manifest.
* **Hands-Free Safety System:** Developed an audible alert system to notify drivers of high-occupancy pickup points, reducing the need for visual screen interaction during transit.
* **Instant Broadcast:** A real-time "Driver's Note" feature allowing instant communication of delays or route changes to the entire user base.

---

## ⚙️ How to Use
1.  **Clone the Repo:** `git clone https://github.com/anv039/cab-pickup-tracker.git`
2.  **Configuration:** Update the `firebaseConfig` object in `index.html` with your own API credentials.
3.  **Launch:** Open `index.html` in any modern web browser.

---

