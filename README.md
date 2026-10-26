# ⚡ REROUTER — Quantum-Integrated Urban Traffic & Signal Grid

**REROUTER** is a futuristic, highly animated single-page web application visualizing quantum-integrated algorithms (QAOA and Quantum Annealing) for real-time metropolitan traffic routing, synchronized green-wave signal timing, and autonomous smart-city incident rerouting.

---

## 🌟 Key Features

### 1. 🔐 Clearance Onboarding & Google OAuth
- **Google Sign-In Simulation & Verification:** 1-click clearance for transit controllers, quantum architects, and fleet directors, as well as custom operator profiles.
- **Google Maps API Key Setup:** Safe modal to link your personal Google Maps API key (persisted in `localStorage`), with automated format validation and live feedback.
- **Autonomous Simulation Mode:** Zero-dependency fallback that simulates metropolitan traffic flows, green waves, and incidents directly in browser vectors without requiring API keys or incurring quota usage.

### 2. 🌗 Dynamic Dual-Theme Architecture
- **Quantum Dark Mode (Default):** Deep slate `#0B0F19`, neon cyan `#00F2FE`, glowing purple `#7F00FF`, and radioactive emerald accents.
- **Smart City Light Mode:** Crisp light grey/white `#F8FAFC`, vivid blues, soft glass gradients, and high-contrast typography.

### 3. ⚛️ Animated "Quantum Traffic Impact Core" Hero Section
- **Interactive Quantum Processor Hub:** Concentric counter-rotating orbits, glowing circuit conduits, and pulsating logical qubit states.
- **Interactive Quantum Pulse:** Inject simulated annealing pulses with particle bursts and canvas confetti.
- **Live Impact Metric Telemetry:**
  - *Global Congestion Reduction Index:* **84.3% Gridlock Collapse**
  - *Air Quality & Emission Index:* **Grade A+ Zero-Idling Zone** (142+ Tons CO2 diverted)
  - *Safety & Collision Shield:* **99.8% Hazard Deflection**
  - *Self-Repairing Grid Status:* **4.2 ms Lattice Latency**

### 4. 🎛️ 5-Step Quantum Process & Impact Modules
Interactive step-by-step card workflow with real-time algorithm previews and technical architecture breakdowns:
1. **Massive Data Gathering:** 4.2M events/sec IoT, V2X, and LiDAR stream ingestion.
2. **Multi-Layer Data Preparation:** QUBO Hamiltonian cost function formulation ($H = \sum w_{ij} x_i x_j$).
3. **Advanced Quantum Simulation:** QAOA variational circuit execution across $2^{128}$ parallel combinatorial paths.
4. **Distributed Routing & Green Waves:** Phase offset synchronization for 48 km/h non-stop arterial corridors.
5. **Real-Time Implementation & Incident Response:** 12 ms dynamic bypass recalculations for collisions and emergency lanes.

### 5. 🗺️ Live Traffic Simulation Engine
- Interactive city vector grid with animated traffic flow.
- Red congested routes transitioning smoothly into glowing green "Quantum Optimized" paths.
- Synchronized "Green Wave" traffic signals showing propagating phase offsets.
- Interactive incident injector: spawn **Accidents**, **Road Construction**, or **Emergency Waves** and watch dynamic bypass arcs route traffic around bottlenecks in real time.
- Playback controls: Play/Pause, 1x/2x/5x speed multiplier, and grid reset.

---

## 🚀 Quickstart Guide

### 1. Start Development Server
```bash
npm run dev
```
Open your browser at `http://localhost:5173`.

### 2. Build for Production
```bash
npm run build
```

---

## 📁 Project Structure

```
├── index.html                   # HTML entry with Google fonts & metadata
├── vite.config.js               # Vite bundler configuration & alias
├── tailwind.config.js           # Custom themes, colors, and neon animations
├── postcss.config.js            # PostCSS plugin setup
└── src/
    ├── main.jsx                 # React root mount
    ├── App.jsx                  # Main application wrapper
    ├── context/
    │   ├── ThemeContext.jsx     # Dark Quantum vs Smart City Light state
    │   └── AuthContext.jsx      # Google OAuth & Google Maps API key state
    ├── components/
    │   ├── Navbar.jsx           # Top header, branding, quick links, theme & auth
    │   ├── AuthModal.jsx        # Google login & Google Maps API configuration modal
    │   ├── QuantumCore.jsx      # Animated processor hub & 4 live metric widgets
    │   ├── WorkflowSteps.jsx    # 5-step quantum pipeline interactive cards
    │   ├── InteractiveMap.jsx   # Live traffic simulation & green wave engine
    │   └── Footer.jsx           # System diagnostics & telemetry footer
    └── styles/
        └── globals.css          # Glassmorphism, neon glows, flow animations
```
