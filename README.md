
# GraphPath

### Interactive Graph Algorithm and Pathfinding Visualizer

GraphPath is a web-based educational platform designed to help users understand graph traversal and pathfinding algorithms through interactive and animated visualizations.

Instead of simply reading how an algorithm works, users can explore graphs, create obstacles, select algorithms, and observe how different algorithms search for a path from a starting node to a destination.

The project aims to make graph algorithms easier to understand through visual learning, practical experimentation, and step-by-step execution.

---

## Overview

GraphPath provides an interactive environment for exploring graph algorithms and understanding how they operate in different scenarios.

The initial version focuses on a grid-based pathfinding visualizer where users can:

- Create and modify a grid.
- Set starting and destination nodes.
- Add obstacles and walls.
- Select different pathfinding algorithms.
- Visualize node exploration and path reconstruction.
- Observe algorithm performance and results.

The project is designed with a modular architecture so that additional algorithms and custom graph visualization features can be introduced in future versions.

---

## Features

### Interactive Grid

- Interactive grid-based environment.
- Customizable starting and destination nodes.
- Wall and obstacle placement.
- Grid reset and clear functionality.
- Random maze generation.

### Algorithm Visualization

- Animated visualization of graph traversal.
- Step-by-step exploration of nodes.
- Visualization of the final path.
- Adjustable animation speed.
- Play, pause, and reset controls.

### Supported Algorithms

| Algorithm | Description |
|---|---|
| Breadth-First Search (BFS) | Explores nodes level by level and finds the shortest path in an unweighted graph. |
| Depth-First Search (DFS) | Explores as deeply as possible before backtracking. |
| Dijkstra's Algorithm | Finds the minimum-cost path in a graph with non-negative edge weights. |
| A* Search | Uses a heuristic to guide the search toward the destination. |

### Performance Analysis

The visualizer aims to display useful performance metrics, including:

- Number of explored nodes.
- Path length or path cost.
- Algorithm execution time.

These metrics help users compare the behavior and efficiency of different algorithms.

---

## Technologies Used

### Frontend

- **React.js** — Building the user interface using reusable components.
- **Vite** — Development server and frontend build tool.
- **JavaScript** — Implementing algorithms and application logic.
- **Tailwind CSS** — Styling and responsive interface design.
- **HTML5 Canvas** — Rendering and visualizing the grid and graph elements.

### Backend

- **Node.js** — JavaScript runtime for backend development.
- **Express.js** — Building RESTful APIs.
- **MongoDB** — Storing persistent application data.

The backend will support features such as saving and retrieving user-created mazes and graphs as the project develops.

---

## System Architecture

GraphPath follows a modular architecture consisting of the following major components:

- **User Interface:** Provides controls for grid interaction, algorithm selection, and visualization.
- **Graph Management:** Handles graph representation, nodes, edges, neighbors, and obstacles.
- **Algorithm Processing:** Implements graph traversal and pathfinding algorithms.
- **Visualization Engine:** Animates algorithm execution and displays the explored nodes and final path.
- **Performance Analysis:** Collects and displays algorithm performance metrics.
- **Backend Services:** Provides API endpoints and persistent storage for saved graph configurations.

The modular design allows individual components to be developed, tested, and extended independently.

---

## Project Structure

```text
GraphPath/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── algorithms/
│   │   ├── data-structures/
│   │   ├── graph/
│   │   ├── visualization/
│   │   ├── hooks/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   └── src/
│       ├── config/
│       ├── models/
│       ├── controllers/
│       ├── routes/
│       ├── middleware/
│       └── server.js
│
├── docs/
│   ├── proposal/
│   └── diagrams/
│
├── README.md
└── .gitignore
```

The project structure may evolve as new features and modules are implemented.

---

## Getting Started

Follow these instructions to set up GraphPath locally.

### Prerequisites

Make sure the following software is installed:

- [Node.js](https://nodejs.org/)
- npm
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/) (recommended)

### Clone the Repository

```bash
git clone https://github.com/RiddhamAcharya/GraphPath.git
```

Navigate to the project directory:

```bash
cd GraphPath
```

### Set Up the Frontend

Navigate to the frontend directory:

```bash
cd frontend
```

Install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173
```

### Set Up the Backend

Backend setup instructions will be added when the backend implementation is introduced.

---

## How to Use

Once the visualizer is implemented, users will be able to:

1. Open the GraphPath visualizer.
2. Create a grid and select the starting and destination nodes.
3. Add walls or obstacles to the grid.
4. Choose a graph algorithm.
5. Start the visualization.
6. Observe the explored nodes and final path.
7. Compare the performance of different algorithms.

---

## Future Enhancements

The project may be extended with the following features:

- Custom graph creation using nodes and edges.
- Grid-based and node-based visualization modes.
- Weighted graphs and customizable edge costs.
- Algorithm comparison mode.
- Interactive algorithm explanations.
- Saved mazes and graph configurations.
- User-created graph collections.
- Additional graph algorithms and data structures.

---

## Educational Objectives

GraphPath is developed as an academic project with the objective of applying concepts from data structures, algorithms, and web development to a practical application.

The project provides an opportunity to:

- Understand graph representations and traversal techniques.
- Implement and analyze graph algorithms.
- Apply data structures such as queues, stacks, and priority queues.
- Develop interactive web applications using modern technologies.
- Explore algorithm performance through practical visualization.

---

## Contributors

Developed by the GraphPath project team as part of the **COMP 206** course project.

---

## License

This project is currently developed for academic purposes.

A license will be added if the project is released for broader use.
