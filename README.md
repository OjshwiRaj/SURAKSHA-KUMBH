# Suraksha Kumbh (सुरक्षा कुंभ)
### Maha Kumbh Central Command & Pilgrim Safety Network

**Suraksha Kumbh** is a real-time crowd safety, disaster management, and resource allocation platform connecting the central **Mela Command Center** with the **Pilgrim Companion App** for high-density religious gatherings and emergency coordination.

## 🚀 Key Modules & Capabilities

*   **Integrated Resource Command**: Real-time inventory tracking, crowd logistics, smart auto-allocation, and 1-tap direct dispatch across all Ghat sectors (Water, Mahaprasad, Ambulances, Medical Kits, Blankets, Life Jackets, Crowd Barriers).
*   **Geospatial Crowd Radar**: Interactive Leaflet maps tracking connected pilgrims, live SOS distress beacons, and medical triage.
*   **Stampede Prevention Routing**: Intelligent load-balancing routing that directs even and odd pilgrim IDs to distinct safe corridors and evacuation zones to prevent bottlenecks.
*   **Voice Guard SOS**: Hands-free distress detection triggered by saying **"Help"** or **"Bachao"** with 5-second cancel overlay.
*   **AI Face Matching**: Instant on-device camera face matching (`face-api.js`) to find missing pilgrims and children.
*   **Offline Mesh Simulation & SMS Fallback**: 868MHz simulated radio packet relay and geo-coded emergency SMS backup.
*   **Multi-Lingual Support**: Full localization for English, हिन्दी (Hindi), मराठी (Marathi), and বাংলা (Bengali).

## 🛠️ Usage

### 1. Installation
```bash
npm install
```

### 2. Run
```bash
PORT=3001 npm start
```
*   Server runs over HTTPS with self-signed certificates (required for Camera/Microphone APIs).
*   Accept the security warning in your browser (**Advanced** -> **Proceed to localhost**).

### 3. Open Interfaces
*   **Command Center**: [https://localhost:3001](https://localhost:3001)
*   **Pilgrim Companion App**: [https://localhost:3001/user](https://localhost:3001/user)

## 🏗️ Architecture
*   **Frontend**: HTML5, Tailwind CSS, Leaflet.js, Face-API.js
*   **Backend**: Node.js, Express, Socket.IO
*   **Protocol**: HTTPS (Local), Simulated Mesh Radio (868MHz logic)

---
**Suraksha Kumbh** — *Dedicated to Pilgrim Safety and Resilient Crowd Management*
