# Sorting Algorithm Visualizer (C++)

A graphical visualizer of sorting algorithms implemented in C++.  
This tool visually demonstrates how algorithms like Bubble Sort, Insertion Sort, or Quick Sort operate step-by-step.

---

##  Overview

- **Tech stack**: e.g. C++17 + SDL2 (or graphics.h, SFML, etc.)
- **Visualization**: Displays elements as bars, animates swaps and comparisons in real-time
- Great for learning how algorithms work, ideal for teaching and demoing.

---

##  Supported Algorithms

- Bubble Sort
- Insertion Sort
- (Add more as implemented—e.g., Selection Sort, Merge Sort, Quick Sort)

---

##  Project Structure

sorting-visualizer/
├── include/
│ └── Visualizer.hpp
├── src/
│ ├── main.cpp
│ ├── BubbleSortVisualizer.cpp
│ └── GraphicsController.cpp
├── assets/ # images, fonts (optional)
├── CMakeLists.txt # or Makefile
├── README.md
└── LICENSE


---

##  Getting Started

### Prerequisites

- C++ compiler with C++17 support
- SDL2 library (or other chosen graphics library)

### Build (CMake example)

```bash
mkdir build && cd build
cmake ..
cmake --build .
```

Or compile directly (if using SDL2):

```bash
g++ -std=c++17 src/*.cpp -Iinclude -lSDL2 -o SortingVisualizer
```

Usage

```bash
./SortingVisualizer  # runs the visualizer
```

Controls (example):

Space : Start sorting

R : Reset / shuffle array

1/2/3 : Choose algorithm (Bubble, Insertion, etc.)

# Sorting Algorithm Visualizer (C++)

A graphical visualizer of sorting algorithms implemented in C++.
This tool visually demonstrates how algorithms like Bubble Sort, Insertion Sort, or Quick Sort operate step-by-step.

---

##  Overview

- **Tech stack**: e.g. C++17 + SDL2 (or graphics.h, SFML, etc.)
- **Visualization**: Displays elements as bars, animates swaps and comparisons in real-time
- Great for learning how algorithms work, ideal for teaching and demoing.

---

##  Supported Algorithms

- Bubble Sort
- Insertion Sort
- (Add more as implemented—e.g., Selection Sort, Merge Sort, Quick Sort)

---

##  Project Structure

sorting-visualizer/
├── include/
│ └── Visualizer.hpp
├── src/
│ ├── main.cpp
│ ├── BubbleSortVisualizer.cpp
│ └── GraphicsController.cpp
├── assets/ # images, fonts (optional)
├── CMakeLists.txt # or Makefile
├── README.md
└── LICENSE

---

##  Getting Started

### Prerequisites

- C++ compiler with C++17 support
- SDL2 library (or other chosen graphics library)

### Build (CMake example)

```bash
mkdir build && cd build
cmake ..
cmake --build .
```

Or compile directly (if using SDL2):

```bash
g++ -std=c++17 src/*.cpp -Iinclude -lSDL2 -o SortingVisualizer
```

Usage

```bash
./SortingVisualizer  # runs the visualizer
```

Controls (example):

Space : Start sorting

R : Reset / shuffle array

1/2/3 : Choose algorithm (Bubble, Insertion, etc.)

Up/Down : Increase/Decrease speed

---

##  Step 5: Next Actions

- Initialize the repo locally or directly on GitHub and clone it.
- Create the above structure using folders and placeholder `.cpp`/`.hpp` files.
- Write visualizer logic gradually: start with implementing bubble sort and drawing bars.
- Test the visual feedback thoroughly and tweak UI/UX (colors, delay, control keys).
- Commit often and push to GitHub.
- Use the README as the documentation for users and contributors.

Let me know your preferred graphics library (e.g., SDL2, SFML, graphics.h), and I can help draft the **CMakeLists.txt** or provide starter code snippets for rendering the bar animation next!
