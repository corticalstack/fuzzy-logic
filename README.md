# 🧠 Fuzzy Logic Implementation and Examples

A comprehensive Python implementation of fuzzy logic concepts using the scikit-fuzzy library, with visualizations and practical examples.

## Description

This repository provides a practical introduction to fuzzy logic concepts through Python implementations. It demonstrates various aspects of fuzzy logic systems including membership functions, fuzzy operations, defuzzification methods, and practical applications like the tipping problem. The code uses the scikit-fuzzy library and includes visualizations to help understand the concepts.

## 🔍 Features

- **Membership Functions**: Implementation and visualization of various membership functions (triangular, trapezoidal, sigmoid, Gaussian, etc.)
- **Fuzzy Logic Operations**: Demonstrations of fuzzy NOT, AND, OR operations
- **Defuzzification Methods**: Examples of different defuzzification techniques (centroid, bisector, mean of maximum, etc.)
- **Practical Problems**: Application of fuzzy logic to real-world problems like restaurant tipping
- **Comparison with Non-Fuzzy Approaches**: Contrasting fuzzy logic with traditional approaches

## 🛠️ Prerequisites

- Python 3.x
- NumPy
- scikit-fuzzy
- Matplotlib
- mpl_toolkits (for 3D visualizations)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/corticalstack/fuzzy-logic.git
cd fuzzy-logic

# Install required packages
pip install numpy scikit-fuzzy matplotlib
```

## 📊 Examples

### Membership Functions
The repository demonstrates various membership functions used in fuzzy logic:
- Triangular and Trapezoidal functions
- Sigmoid, S-function, Z-function, and Pi-function
- Gaussian and Bell-shaped functions

### Fuzzy Logic Operations
Implementation of basic fuzzy logic operations:
- Fuzzy NOT (complement)
- Fuzzy AND (intersection)
- Fuzzy OR (union)

### Defuzzification Methods
Various methods to convert fuzzy output to a crisp value:
- Centroid method
- Bisector method
- Mean of Maximum (MOM)
- Smallest of Maximum (SOM)
- Largest of Maximum (LOM)

### Tipping Problem
A classic example of fuzzy logic application where service quality (and food quality in some examples) is used to determine the appropriate tip amount:
- Basic implementation with one input (service quality)
- Mamdani inference method with two inputs (service and food quality)
- Sugeno inference method with two inputs
- Comparison with non-fuzzy approaches (constant, linear, and more complex mappings)

## 📚 Resources

- [Fuzzy Logic - Wikipedia](https://en.wikipedia.org/wiki/Fuzzy_logic)
- [scikit-fuzzy Documentation](https://pythonhosted.org/scikit-fuzzy/)
- [Fuzzy Control Systems: An Introduction](https://www.sciencedirect.com/topics/engineering/fuzzy-control-system)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
