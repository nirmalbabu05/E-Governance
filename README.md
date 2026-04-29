# 🏙️ Smart City | AI-Powered Civic Complaint Portal
**Decentralized E-Governance with Edge-AI and Tamper-Proof Cryptographic Geotagging**

## 🚀 Overview

**Smart City** is a next-generation, decentralized e-governance and workforce management progressive web application (PWA). Designed to solve critical flaws in modern municipal management, the platform automates complaint triaging, ensures 100% workforce accountability, and provides real-time data synchronization for city administrators.

Taking civic tech to the next level, the system completely bypasses sluggish cloud processing by integrating **Edge-AI (TensorFlow.js)** directly in the browser. It instantly fuses citizen text input with live camera feeds to autonomously categorize issues and assign priorities. To completely eradicate financial fraud and "ghost repairs", the platform employs a **Cryptographic Geotagging** engine that permanently burns hardware-locked GPS coordinates and timestamps directly into image pixels, creating mathematically secure proof-of-work.

## ✨ Key Features

* 🤖 **Multimodal Edge-AI Triage:** Utilizes in-browser machine learning (MobileNet V2) to fuse visual image tensors with human-typed text, autonomously classifying civic issues (e.g., Potholes, Solid Waste) with zero server latency.
* 📸 **Tamper-Proof Cryptographic Geotagging:** A restricted live-camera protocol that blocks gallery uploads and uses the HTML5 Canvas API to permanently burn high-accuracy satellite GPS coordinates and NTP server time into repair image pixels.
* 💬 **Fuzzy-Logic NLP Chatbot:** An integrated virtual assistant powered by the Levenshtein Distance algorithm that tolerates typos (e.g., "gerbage" -> "garbage") to help citizens track statuses and find government schemes seamlessly.
* ⚡ **Event-Driven Commissioner Dashboard:** Powered by a NoSQL backend, providing instant WebSocket updates without page reloads. Features predictive analytics to monitor resolution velocity and identify infrastructure bottlenecks.
* 🌍 **Live GIS Heatmap:** Interactive mapping using Leaflet.js that visually plots reported issues and workforce activity across various municipal zones in real-time.
* 🏆 **Gamified Workforce Leaderboard:** Automatically credits points to workers and supervisors based on cryptographically verified task completions to dynamically boost efficiency.
* 🔐 **Dynamic Role-Based Access Control (RBAC):** A single unified PWA that intelligently morphs its UI and permissions based on the logged-in role (Citizen, Worker, Supervisor, Commissioner, Admin).

## 🛠️ Tech Stack

**Frontend Architecture**
* HTML5 & Semantic Markup
* CSS3 (Custom Government Theme, Glassmorphism, Dark/Light Mode)
* Vanilla JavaScript (ES6+, DOM Manipulation, Asynchronous API handling)
* Progressive Web App (PWA) Standards

**Artificial Intelligence & Algorithms**
* **TensorFlow.js (`@tensorflow/tfjs`):** Client-side inference via MobileNet V2.
* **Custom NLP Engine:** Levenshtein Distance Algorithm for fuzzy string matching.
* **Multimodal Fusion Logic:** JavaScript algorithms linking AI vision vectors with text context.

**Backend & Database**
* **Google Firebase Realtime Database:** NoSQL JSON tree for blazing-fast, event-driven data sync.
* **Firebase Authentication:** Secure login and session management via JWT.

**Hardware APIs & Cryptography**
* **HTML5 Geolocation API:** Forced high-accuracy mode directly pinging satellite hardware.
* **WebRTC / MediaDevices API:** Hijacks device camera to enforce live-capture only.
* **HTML5 Canvas API:** Pixel-level cryptographic watermarking of spatial and temporal data.

**Data Visualization & Mapping**
* **Leaflet.js & OpenStreetMap:** Real-time GIS heatmap rendering.
* **Chart.js:** Dynamic predictive analytics and performance graphs.

## 💻 Running the Project Locally

### 📦 Installation

Since this project relies on a serverless NoSQL architecture and Edge-AI, setting up the environment locally is incredibly fast and requires no complex backend installations. Follow these steps:

**1️⃣ Clone the repository**
```bash
git clone [https://github.com/nirmalbabu05/E-Governance.git](https://github.com/nirmalbabu05/E-Governance.git)
cd E-Governance

**📂 2. Open the Project**
Open the project folder in your favorite code editor (e.g., VS Code).

```bash
code .

**⚙️ 3. Start a Local Development Server**
If you are using VS Code, install the Live Server extension and click "Go Live" on index.html. Alternatively, you can use Python's built-in server:

Bash
python -m http.server 8000

**🌐 4. View in Browser**
Open your browser and navigate to: http://localhost:8000/

Note: Ensure you allow camera and location permissions in your browser for the Edge-AI and Geotagging features to function properly.

📜 License
This project was built as a final-year engineering endeavor to showcase modern full-stack capabilities, Edge-AI integration, and robust anti-fraud software architecture in the e-governance sector.

Made with ❤️ by Nirmal Babu V M
