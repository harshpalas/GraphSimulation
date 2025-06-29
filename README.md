# Graph Simulation Visualizer

Graph Simulation Visualizer is an interactive web application for visualizing and learning fundamental graph algorithms. It provides step-by-step, animated explanations of algorithms like Dijkstra's shortest path, Breadth-First Search (BFS), Depth-First Search (DFS), and Minimum Spanning Tree (MST) algorithms (Prim's and Kruskal's). This tool is ideal for students, educators, and anyone interested in understanding how graph algorithms work in a visual and intuitive way.

---

## 🚀 Features

- **Landing Page:**  
  - Modern, animated introduction to graph algorithms and their importance.
  - Quick navigation to all algorithm visualizers.

- **Dijkstra Visualizer:**  
  - Step-by-step animation of Dijkstra's shortest path algorithm.
  - Selectable start and end nodes.
  - Shows path, cost, and distance updates in real-time.
  - Typewriter explanations for each step.
  - Play/Pause controls for learning at your own pace.

- **BFS Visualizer:**  
  - Visualizes Breadth-First Search on multiple graph types (binary tree, grid).
  - Animated traversal order and edge highlighting.
  - Step explanations and play/pause controls.
  - Switch between different graph structures.

- **DFS Visualizer:**  
  - Visualizes Depth-First Search on multiple graph types.
  - Animated traversal, backtracking, and edge highlighting.
  - Step explanations with typewriter effect.
  - Play/Pause and graph switching.

- **MST Visualizer:**  
  - Visualizes Prim's and Kruskal's Minimum Spanning Tree algorithms.
  - Step-by-step edge selection and MST construction.
  - Detailed beginner-friendly explanations.
  - Pause/Play and Reset controls.

- **Responsive UI:**  
  - Built with Tailwind CSS for a modern, mobile-friendly experience.
  - SVG-based graph rendering for smooth, scalable visuals.

---

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Styling:** Tailwind CSS (via CDN)
- **Visualization:** SVG for dynamic graph rendering and animation
- **No frameworks or build tools required** – runs directly in the browser

---

## 💡 Impact

- **Educational:** Makes abstract graph algorithms tangible and easy to understand.
- **Interactive:** Users can control the pace, select start/end nodes, and switch graph types.
- **Engaging:** Typewriter explanations, animated transitions, and playful UI keep learning fun.
- **Accessible:** No installation or backend required; works in any modern browser.

---

## ⚙️ Implementation Overview

- **File Structure:**
  - `index.html`: Landing page with animated intro and navigation.
  - `dj.html`: Dijkstra's algorithm visualizer.
  - `bfs.html`: BFS visualizer (multiple graphs).
  - `dfs.html`: DFS visualizer (multiple graphs).
  - `mini.html`: MST visualizer (Prim's and Kruskal's).
- **Algorithm Logic:**  
  - All algorithms are implemented in JavaScript with clear, stepwise animation and explanations.
  - Uses SVG for drawing nodes, edges, and highlights.
  - Typewriter and step-by-step explanations are synchronized with the animation.
- **Controls:**  
  - Play/Pause, Reset, and Graph Switch buttons for full user control.
  - Select menus for choosing start/end nodes where applicable.

---

## 📦 Getting Started

1. **Clone or Download the Repository:**
   ```sh
   git clone https://github.com/yourusername/graphsimulation.git
   cd graphsimulation
   ```

2. **Open in Browser:**
   - Open `index.html` in your preferred web browser.
   - No server or build step required.

3. **Explore:**
   - Click on any algorithm icon to start visualizing and learning!

---

## 📄 License

MIT License

---

## 🙏 Credits

Developed by [Your Name].  
Icons and illustrations from open web sources.  
Special thanks to the open-source community for inspiration.

---
