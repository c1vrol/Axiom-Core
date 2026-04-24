# Axiom-Core
Central Data of Axiom HUB.

Axiom is a high-performance, enterprise-grade HUB designed for advanced environment analysis, system diagnostics, and workspace manipulation. Originally authored and developed by **@c1vrol**, Axiom serves as a centralized suite for multiple independent tools, each built to provide professional-level insights into the game engine's state.

## 🚀 Project Overview

Unlike traditional monolithic scripts, Axiom is built on a modular philosophy. Every tool within the HUB was developed independently to ensure maximum stability and precision. Whether you are auditing executor capabilities or performing deep-tissue property inspection, Axiom provides the interface you need.

## 🛠 Key Modules

### 📊 Telemetry Hub
A precision diagnostics tool inspired by the Axiom Audit Protocol. It provides real-time tracking for:
*   **Performance Metrics:** Frame Rate (FPS), Memory Usage (RAM), and Network Latency (Ping).
*   **Instance Analytics:** Detailed counts of Parts, MeshParts, Sounds, and RemoteEvents within the workspace.
*   **Network Logger:** Monitoring of remote traffic and system stability.

### 🔍 Workspace Searcher & Properties Inspector
A desktop-class interface for exploring the game's DataModel. 
*   **Hierarchical Browser:** Navigate through services and objects with a familiar tree-view.
*   **Advanced Inspector:** View and modify object properties in real-time with support for Enums, Colors, and Booleans.
*   **Snapping UI:** Dockable panels that allow for a customized workspace layout.

### 👁️ Universal ESP (Extra Sensory Perception)
A highly customizable visual enhancement suite featuring:
*   **Multi-Language Support:** Available in English, Spanish, and Portuguese.
*   **Dynamic Highlighting:** Bounding box and silhouette tracking with health bar integration.
*   **Performance Optimized:** Uses a specialized caching system to maintain high framerates even in crowded servers.
*   **Game-Specific Logic:** Includes tailored features for specific titles (e.g., "Flee the Facility" style games).

### ⚖️ Axiom Audit Protocol
An "Enterprise Edition" executor testing utility. It runs a series of integrity scans to determine the execution level of your environment, probing for:
*   Metamethod proxying and V-Table detouring.
*   Metatable access and object reference spoofing.
*   C-Closure encapsulation and thread identity escalation.

### 🎯 Additional Utilities
*   **Distance Meter:** A raycast-based measurement tool for calculating exact distances in meters or studs.
*   **Auto-Farm Modules:** Specialized scripts for automated object interaction (e.g., Bag collection).
*   **Traverse X-Ray:** Optimized ESP for specific organizational structures like Police/Citizen models.

## 💻 Installation & Usage

To initialize the Axiom environment, execute the main loader in your compatible environment:

```lua
-- Axiom HUB Loader
loadstring(game:HttpGet("YOUR_LINK_HERE"))()
```

## 🎨 UI Philosophy

Axiom utilizes the **Axiom Theme**, a dark-mode aesthetic focused on:
*   **Clarity:** High-contrast text and muted backgrounds.
*   **Responsiveness:** Smooth UI transitions using TweenService and CanvasGroups.
*   **UX:** Intuitive navigation with sidebar-based layouts and minimized "minimalist" modes.

## 📜 Credits & Disclaimer

*   **Author:** [c1vrol](https://github.com/c1vrol)
*   **Development:** All tools within this HUB are developed independently.

---

*Disclaimer: Axiom HUB is intended for educational and analytical purposes. Always ensure compliance with the terms of service of the platforms you interact with.*
