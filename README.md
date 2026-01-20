---

# NumLibCpp — High-Performance Numerical Methods Library

**NumLibCpp** is a modern C++17 library designed for scientific computing and engineering applications. It provides a suite of robust implementations for essential numerical algorithms, focusing on efficiency, modularity, and clean code practices.

[![Language](https://img.shields.io/badge/language-C%2B%2B17-blue.svg)](https://en.cppreference.com/w/cpp/17)
[![Build System](https://img.shields.io/badge/build-CMake-green.svg)](https://cmake.org/)

## 🚀 Key Features

The library covers a wide range of numerical challenges:

*   **Linear Algebra:** Solving systems of linear equations using **Gaussian Elimination**.
*   **Interpolation:** High-precision **Lagrange Interpolation**.
*   **Approximation:** Optimized algorithms for data fitting (e.g., Least Squares).
*   **Numerical Integration:** Reliable integration using **Simpson’s Rule**.
*   **Differential Equations:** Solving Ordinary Differential Equations (ODEs) via the **4th Order Runge-Kutta Method (RK4)**.
*   **Root-Finding:** Solving non-linear equations using the **Secant Method**.
*   **Numerical Differentiation:** Gradient estimation using the **Central Difference Method**.

## 🛠 Project Structure

The project follows industry-standard directory layouts for easy integration and scalability:

```text
NumLibCpp/
├── include/NumLibCpp/   # Header-only interfaces and templates
├── src/                 # Implementation files
├── tests/               # Unit tests ensuring algorithm correctness
├── examples/            # Ready-to-run usage demonstrations
├── CMakeLists.txt       # Unified build configuration
└── README.md            # Documentation
```

## 💻 Tech Stack & Requirements

*   **Standard:** C++17.
*   **Build System:** CMake 3.10+.
*   **Compiler:** GCC, Clang, or MSVC.

## 🏗 Installation & Building

### 1. Clone the repository
```bash
git clone https://github.com/your-username/NumLibCpp.git
cd NumLibCpp
```

### 2. Configure and Build
```bash
mkdir build && cd build
cmake ..
cmake --build .
```

## 🧪 Testing and Quality Assurance

```bash
# Run all unit tests from the build directory
./tests/run_all_tests
```

## 📚 Examples

Check the `examples/` directory to see how to integrate NumLibCpp into your own projects. Example outputs include:
- `math_functions.exe`: Demonstration of general calculus features.
- `engineering_problem.exe`: Solving real-world ODE and linear system scenarios.
