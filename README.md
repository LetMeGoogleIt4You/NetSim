# 🌐 NetSim Pro

**A visual network topology simulator running entirely in the browser.** NetSim Pro helps network engineers and students visualize routing decisions, metric calculations, and failure scenarios using Dijkstra's algorithm and Equal-Cost Multi-Path (ECMP) logic.

### 🚀 [Click here to test NetSim](https://LetMeGoogleIt4You.github.io/NetSim/)

---

## ✨ Key Features

* **Pathfinding Visualization:** Automatically calculates the shortest path based on link metrics.
* **ECMP Support:** visualizes "Equal-Cost Multi-Path" routing when multiple paths share the same total metric.
* **Packet Flow Animation:** Visualizes traffic direction and flow on active routes.
* **Failure Simulation:** "Kill" specific nodes to see how the network automatically reroutes traffic.
* **Interactive Canvas:** Pan, zoom, and drag nodes on an infinite grid.
* **Smart Layouts:** Nodes automatically position their labels to avoid overlapping with links.
* **Save & Load:** Export your topologies to JSON and load them later (or move them between computers).
* **Theming:** Toggle between Cyberpunk (Dark) and Engineering (Light) modes.

## 🎮 Controls & Shortcuts

| Action | Control |
| :--- | :--- |
| **Pan Canvas** | Left-Click + Drag (on empty space) |
| **Zoom** | Sidebar Slider |
| **Select Node** | Left-Click Node |
| **Multi-Select** | `Shift` + Left-Click Nodes |
| **Context Menu** | Right-Click (Canvas, Node, or Link) |
| **Delete Item** | `Delete` Key |
| **Edit Properties** | Double-Click Node or Link |


## 🛠️ How to Use

1.  **Add Nodes:** Right-click anywhere on the grid and select "Add Router Here".
2.  **Connect Links:** Right-click a node $\to$ "Connect Link", then click a second node.
3.  **Set Metrics:** Double-click a link to change its cost (Metric).
4.  **Run Traffic:** Right-click a node $\to$ "Start Path", then left-click your Destination node.
5.  **Simulate Failure:** Double-click a node or link and uncheck "Active" to simulate a  failure.

## 📦 Offline / Air-Gapped Usage

This tool is can to run without a backend server. To run it in a secure/offline environment:


1.  Open `index.html` in offline folder with any modern browser (Chrome, Edge, Firefox).
2.  Option: `python -m http.server 8000` in the same folder

---

*Built with React, Tailwind CSS, and SVG (and with AI, I cant code for shit) .*
