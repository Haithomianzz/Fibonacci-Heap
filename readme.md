# Fibonacci Heap Visualization

This project was developed as a group assignment for a university course. The team members collaborated to create a visualization tool for Fibonacci Heaps using C++ and the Dear ImGui library. The following GitHub usernames represent the contributors to this project: [@Omar-Helwa](https://github.com/Omar-Helwa), [@PeterArsanious2004](https://github.com/PeterArsanious2004), [@Ahmed-Fahmy00](https://github.com/Ahmed-Fahmy00), [@Haithomianzz](https://github.com/Haithomianzz), [@BimaAbf](https://github.com/BimaAbf).

We believe that the success of this project is a testament to our shared commitment to teamwork, open communication, and the equitable distribution of workload. We are proud of the collective effort we put forth and the knowledge we gained through this collaborative experience.

## Overview & Goals

The main goal of this project was to create the Fibonacci Heap structure. A Fibonacci Heap is a data structure consisting of a collection of trees satisfying the minimum-heap property. It is particularly useful for implementing priority queues with a better amortized time complexity for operations like insert, decrease key, and delete minimum.

## Features

- **Insert Nodes**: Add nodes with a specified key and name.
- **Extract Minimum**: Remove the node with the minimum key.
- **Modify Key**: Change the key of an existing node.
- **Delete Node**: Remove a node with a specified key.
- **Visualization**: Real-time visualization of the Fibonacci Heap structure.
- **Task Management**: Manage tasks with priorities using the `HospitalTaskManager` class.

## Dependencies

- **C++17** or later
- **GLFW**: For window and context creation
- **OpenGL**: For rendering
- **Dear ImGui**: For the graphical user interface
- **ImGui GLFW and OpenGL3 bindings**: For integrating ImGui with GLFW and OpenGL

## Usage

1. **Run the application**:
    - Execute the built binary from your IDE or terminal.

2. **Interact with the GUI**:
    - Use the control panel to insert, modify, or delete nodes.
    - Visualize the changes in the Fibonacci Heap in real-time.
    - Manage tasks with priorities using the `HospitalTaskManager` interface.

## Code Structure

- `src/`: Contains the source code for the project.
  - `FibHeap.h`: Implementation of the Fibonacci Heap.
  - `DoublyCircularLinkedList.h`: Implementation of the Doubly Circular Linked List.
  - `Node.h`: Definition of the Node structure.
  - `VisualizeFibonacciHeap.h`: Visualization logic using Dear ImGui.
  - `HospitalTaskManager.h`: Task management logic.
  - `VisualizeTaskManager.h`: Visualization logic for task management using Dear ImGui.
  - `Patient.h`: Definition of the Patient class used in task management.
- `main.cpp`: Entry point of the application.

## Acknowledgements

- [Dear ImGui](https://github.com/ocornut/imgui)
- [GLFW](https://www.glfw.org/)
- [OpenGL](https://www.opengl.org/)
