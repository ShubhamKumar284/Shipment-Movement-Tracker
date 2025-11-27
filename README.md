**📦 Shipment Movement Tracker**

A C++ program that tracks and analyzes shipment movements between locations using graph-based algorithms. It supports adding shipment routes, detecting cycles, finding the shortest delivery path, and analyzing unique shipment locations.

🚀 Features
✔ Add Shipment Movements

Record movements from one location to another.

✔ Display All Movements

View all shipment transitions in the order they were entered.

✔ Shortest Path Finder

Uses BFS (Breadth-First Search) to find the shortest route between two locations.

✔ Cycle Detection

Detects if any shipment loop exists using DFS recursion stack.

✔ Unique Location Counter

Counts and displays all distinct locations involved in shipment movement.

📘 How It Works

The system models shipment routes as a directed graph, where:

Each location = node

Each movement = directed edge

This allows graph algorithms to analyze shipment flow efficiently.

🛠️ Technologies Used

C++

STL (Standard Template Library)

unordered_map

list

queue

stack

unordered_set


🧠 Future Scope

Real-time GPS / IoT-based shipment tracking

ML-driven route optimization and delay prediction

Dashboard visualization and heatmaps

Cloud database integration

Blockchain-based secure shipment logs

Multi-modal transport support (road/rail/air/sea)

🤝 Contributing

Pull requests and suggestions are welcome!
Feel free to fork this repository and create improvements.
