# Maze Project

## Introduction

The Maze Project is an application designed to create and solve mazes using various algorithms. The project is built with a focus on efficiency and user interaction, featuring a graphical user interface (GUI). The application provides different maze generation and solving techniques, offering users a robust and interactive way to explore maze algorithms.

## Features

- Generation of mazes using different algorithms (e.g., Depth-First Search, Prim's Algorithm).
- Solving mazes using various pathfinding algorithms (e.g., Breadth-First Search, A*).
- Interactive GUI for visualizing maze generation and solving processes.(SFML)
- Ability to customize maze size and complexity.
- Option to save and load mazes for later use.

## Technologies Used

- **C++**: Core language for implementing the algorithms and application logic.
- **SFML**: Used for creating the graphical user interface.
- **CMake**: Build system for managing the build process.
- **Google Test**: Testing framework for unit tests.

## Getting Started

### Prerequisites
- C++17 or higher
- CMake 3.10 or higher
- SFML 2.6.1 or higher

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ramihdedeh/Maze.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Maze
   ```

3. **Create a build directory and navigate into it**:
   ```bash
   mkdir build && cd build
   ```

4. **Configure the project using CMake**:
   ```bash
   cmake ..
   ```

5. **Build the project**:
   ```bash
   make
   ```

### Running the Application

To run the application after building it:

```bash
./MazeApp
```

### Running Tests

To run the unit tests:

```bash
make test
```

### Packaging the Application

To package the application into a distributable format:

```bash
make package
```

## Project Structure

- **CMakeLists.txt**: Contains the CMake configuration for the project.
- **src/**: Contains the C++ source code.
- **include/**: Contains the header files.


## License
This project is licensed under the MIT License. See the LICENSE file for details.

