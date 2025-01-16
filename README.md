# *RTT Algorithm Optimization using Quantum Computing*

## *Overview*
This project explores the enhancement of the Round Trip Time (RTT) algorithm using quantum computing principles. By simulating quantum behavior in classical systems, we aim to improve the accuracy and efficiency of RTT calculations in networking.

The repository contains the full codebase, simulation models, and example outputs showcasing the improvements achieved through our approach.
---
## *Repository Structure*

├── src/  
│   ├── classical_rtt.py          # Baseline classical RTT algorithm  
│   ├── quantum_rtt_simulation.py # Quantum-inspired RTT simulation  
│   ├── utils.py                  # Helper functions for data processing  
│   └── config.json               # Configuration file for parameters  
├── examples/  
│   ├── example_output_1.txt      # Example output 1  
│   └── example_output_2.txt      # Example output 2  
├── requirements.txt              # Required libraries with versions  
└── README.md                     # Documentation  


---

### **How to Run the Codebase**

Follow the steps below to set up and run the project:

#### **Step 1: Clone the Repository**  
First, clone the repository from GitHub and navigate to the project folder:

```bash
git clone https://github.com/username/Quantum_RTT_Optimization.git
cd Quantum_RTT_Optimization
```

#### **Step 2: Install Required Libraries**  
Make sure you have Python 3.9+ installed. Then, install all the required libraries using:

```bash
pip install -r requirements.txt
```

#### **Step 3: Run the Code**  
To run the classical RTT algorithm:  
```bash
python src/classical_rtt.py
```

To run the quantum-inspired RTT simulation:  
```bash
python src/quantum_rtt_simulation.py
```



---
## *Required Libraries*
- Python 3.9+  
- NumPy 1.24.4  
- SciPy 1.11.0  
- Matplotlib 3.7.2  
- Qiskit 0.43.1 (for optional quantum backends)

---

## *Example Output*

### *Example 1: Classical RTT vs. Quantum-Inspired RTT*

| *Packet Size* | *Classical RTT (ms)* | *Quantum-Inspired RTT (ms)* |  
|-----------------|------------------------|-------------------------------|  
| 64 KB           | 12.3                   | 10.1                          |  
| 128 KB          | 18.5                   | 14.8                          |  

This example demonstrates that the quantum-inspired algorithm reduces the average RTT by approximately 20%
