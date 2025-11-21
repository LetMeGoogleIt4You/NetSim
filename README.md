# 🌐 NetSim Pro

**A visual network topology simulator running entirely in the browser.** NetSim Pro helps network engineers and students visualize routing decisions, metric calculations, and failure scenarios using Dijkstra's algorithm and Equal-Cost Multi-Path (ECMP) logic.

### 🚀 [Launch Live Simulator](https://LetMeGoogleIt4You.github.io/NetSim/)

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
| **Quick Save** | `Enter` (while editing text inputs) |

## 🛠️ How to Use

1.  **Add Nodes:** Right-click anywhere on the grid and select "Add Router Here".
2.  **Connect Links:** Right-click a node $\to$ "Connect Link", then click a second node.
3.  **Set Metrics:** Double-click a link to change its cost (Metric).
4.  **Run Traffic:** Right-click a node $\to$ "Start Path", then left-click your Destination node.
5.  **Simulate Failure:** Double-click a node and uncheck "Node Active" to simulate a power failure/crash.

## 📦 Offline / Air-Gapped Usage

This tool is designed to run without a backend server. To run it in a secure/offline environment:

1.  Download the `index.html` file.
2.  Download the dependencies (`react.js`, `react-dom.js`, `babel.js`, `tailwind.js`) and place them in the same folder.
3.  Update the `<script>` tags in the HTML to point to the local files.
4.  Open `index.html` in any modern browser (Chrome, Edge, Firefox).

---

*Built with React, Tailwind CSS, and SVG.*
