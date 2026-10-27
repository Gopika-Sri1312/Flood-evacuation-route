
# FloodSafe — Smart Flood Evacuation Planner

## 📌 Project Overview

FloodSafe is a flood evacuation planning system designed to help identify shorter evacuation routes, rank available shelters, and allocate evacuation groups based on shelter capacity.

The project demonstrates the practical application of **Design and Analysis of Algorithms (DAA)** concepts to a flood management scenario.

This is an academic prototype that uses sample data. It is not intended for real-time emergency response.

## 🎯 Objectives

- Find the shortest evacuation route between locations.
- Rank shelters based on their distance from the evacuation location.
- Allocate evacuation groups according to available shelter capacity.
- Demonstrate the practical use of graph algorithms, sorting, and greedy techniques.
- Provide a simple and user-friendly interface for exploring evacuation plans.

## ✨ Features

- **Shortest Route Finding:** Identifies the shortest path between two locations.
- **Shelter Ranking:** Sorts shelters based on distance.
- **Evacuation Group Allocation:** Assigns groups to shelters while considering available capacity.
- **Interactive Map:** Displays sample locations and connections.
- **Capacity Tracking:** Shows shelter capacity and allocation status.
- **Responsive Interface:** Works on desktop and mobile screens.

## 🧠 Algorithms Used

### 1. Dijkstra's Algorithm
Used to find the shortest path between two locations in a weighted graph.

**Purpose:** Minimize the total travel distance during evacuation.

**Time Complexity:** \(O((V + E)\log V)\) with a suitable priority-queue implementation. The simple JavaScript implementation in this prototype may have a different complexity.

### 2. Merge Sort
Used to sort shelters according to their distance from the selected location.

**Time Complexity:** \(O(n\log n)\)

### 3. Greedy Algorithm
Used to allocate evacuation groups to shelters based on available capacity.

**Purpose:** Make allocation decisions while respecting shelter capacity constraints.

**Note:** The greedy approach does not guarantee a globally optimal allocation for every possible scenario.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- SVG for map visualization
- DAA concepts: Graphs, shortest paths, sorting, and greedy algorithms

## 🗺️ Sample Graph

The prototype uses the following sample connections:

| Location 1 | Location 2 | Distance |
|---|---|---:|
| A | B | 2 km |
| A | C | 5 km |
| B | C | 1 km |
| B | D | 4 km |
| C | D | 1 km |
| C | E | 3 km |

**Example:** The shortest route from A to D is:

`A → B → C → D`

Total distance: **4 km**

These values are illustrative and do not represent actual geographic distances.

## 🏠 Sample Shelters

| Shelter | Location | Capacity |
|---|---|---:|
| North Shelter | D | 5 people |
| East Shelter | E | 4 people |

Shelter capacities and evacuation groups are sample inputs for demonstrating the algorithms.

## 🚀 Getting Started

### Prerequisites

- A web browser such as Google Chrome, Microsoft Edge, or Firefox.
- No additional installation is required.

### Run the Project

1. Clone or download this repository.
2. Open the project folder.
3. Locate `index.html`.
4. Double-click `index.html` or open it in your web browser.
5. Use the interface to explore routes, shelter rankings, and group allocation.

The standalone HTML version runs directly in the browser without a backend server.

## 📂 Project Structure

```text
FloodSafe/
├── index.html
└── README.md
```

The repository may also include the Java source files if the Java implementation is maintained separately.

## 📈 Applications

- Academic demonstrations of shortest-path algorithms.
- Evacuation route planning simulations.
- Shelter capacity management prototypes.
- Learning and demonstrating DAA concepts.
- Exploring algorithmic approaches to disaster management.

## 🔮 Future Enhancements

- Integration with real geographical maps.
- Real-time flood and weather data.
- Dynamic road blockage detection.
- Live shelter availability updates.
- More advanced evacuation allocation algorithms.
- Backend and database integration.
- Mobile application support.

## ⚠️ Limitations

- Uses predefined sample locations and distances.
- Does not use real-time flood or road condition data.
- Shelter capacities are illustrative.
- Does not replace official evacuation instructions or emergency services.

## 👩‍💻 Author

**Gopika Sri S S**

- Register Number: 711525BCS037
- Department: B.E. Computer Science and Engineering – A
- Institution: KIT – Kalaignarkarunanidhi Institute of Technology

## 📚 Academic Context

**Subject:** Design and Analysis of Algorithms (DAA)

**Project Title:** Flood Evacuation Route and Shelter Allocation System

---

⭐ This project demonstrates how algorithmic techniques can support the planning of safer and more organized evacuation scenarios.
