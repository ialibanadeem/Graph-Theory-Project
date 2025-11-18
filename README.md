

# 🎮 **Game Level Connectivity Analysis – Graph Theory Project**

This project analyzes a complex video game level using **Graph Theory** concepts such as connectivity, shortest paths, Euler/Hamilton paths, and critical node detection.

The level is modeled as a graph where:

* **Nodes represent rooms/areas**
* **Edges represent paths, doors, tunnels, or connections**

We designed a large, realistic game world called **“The Lost Temple Network”**, divided into three interconnected regions:

* 🏛️ **Ancient Halls**
* ❄️ **Crystal Caves**
* 🏰 **Shadow Fortress**

A total of **20 rooms** and **30+ connections** make the graph rich enough for meaningful analysis.

---

## 🚀 Features

### ✔ **Graph Construction**

* The game map is modeled as an undirected graph using NetworkX.
* Rooms and connections are added as nodes and edges.
* Three regions are visually color-coded for clarity.

### ✔ **Graph Visualization**

* Clean layout using `kamada_kawai_layout`
* Colored nodes based on zones
* Clear and readable node labels
* Interactive graph (PyVis optional)

### ✔ **Graph Analysis**

* Full connectivity check
* Shortest path calculation
* Eulerian path check
* Hamiltonian path feasibility
* Region-level structure clarity

### ✔ **Visual Shortest Path Highlight**

A separate graph highlights the shortest route from the game entrance **(R1)** to the throne room **(S5)**.

---

## 🧠 **Graph Theory Concepts Used**

* **Connectivity**: Ensures all rooms are reachable.
* **Shortest path**: Uses BFS/Dijkstra (handled by NetworkX).
* **Eulerian Path**: Checks if every edge can be visited exactly once.
* **Hamiltonian Path (approx.)**: Determines if visiting each room once is possible.
* **Graph Visualization**: Helps understand level structure and complexity.

---

## 🗺️ **Game Map Overview**

The world consists of three interconnected regions:

### 🏛️ Ancient Halls

* Rooms: R1–R6
* Contains early exploration areas, loops, and shortcuts.

### ❄️ Crystal Caves

* Rooms: C1–C7
* Includes multiple branching paths, hidden loops, and cross-region connections.

### 🏰 Shadow Fortress

* Rooms: S1–S7
* Contains high-level areas, circular paths, and the throne chamber.

---

## 🧩 **Technologies Used**

* **Python**
* **NetworkX** (graph creation + algorithms)
* **Matplotlib** (graph visualization)

---

## 🎨 **Screenshots**

<img width="1260" height="968" alt="image" src="https://github.com/user-attachments/assets/668190de-d1a9-40df-88dd-002f499a05f2" />

---

## 👨‍💻 Team Members (Group of 3)

1. **Zainab Saeed:** Ancient Halls zone, initial graph structure
2. **Aliba Nadeem:** Crystal Caves zone, core algorithms
3. **Syed Saqlain Ahmed Qadri:** Shadow Fortress zone, visualization & analysis


