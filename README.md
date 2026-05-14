# GTA San Andreas Path Nodes Dataset (JSON)

This repository contains the complete network of road, traffic, and pedestrian nodes from **GTA San Andreas** converted into a clean, easy-to-use JSON format. 

Ideal for developers working with **CLEO Redux (JavaScript/TypeScript)**, **SAMP/open.mp**, C++, or external mapping tools who need to implement autonomous driving, GPS systems, or **A* / Dijkstra pathfinding algorithms**.

## 📊 Dataset Structure
The nodes are structured as a Graph/Adjacency List where each node contains its accurate 3D game coordinates ($X, Y, Z$) and an array of linked neighbor nodes.

```json
{
  "1024": {
    "x": 2040.2,
    "y": 1200.5,
    "z": 10.5,
    "links": [1025, 2040]
  }
}
