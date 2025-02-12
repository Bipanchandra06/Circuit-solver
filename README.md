# **General Circuit Solver with Real-Time Visualization**  

### **Overview**  
This project is a **Graphical User Interface (GUI)-based circuit solver** that allows users to design and analyze electrical circuits in real time. It provides an **interactive environment** for adding circuit components, visualizing the circuit structure, and solving for node voltages using **Laplace Transform-based Nodal Analysis**.  

---

## **Features**  
✅ **Graphical Circuit Design** – Add resistors, capacitors, inductors, switches, and voltage sources dynamically.  
✅ **Real-Time Circuit Visualization** – Uses **NetworkX & Matplotlib** to display the circuit structure.  
✅ **Laplace Transform-based Analysis** – Solves AC/DC circuits, modeling capacitors and inductors with initial conditions.  
✅ **Multiple Voltage Source Types** – Supports **sinusoidal, cosine, and DC voltage inputs** for dynamic circuit simulation.  
✅ **Symbolic Computation with SymPy** – Uses **symbolic mathematics** to solve for node voltages efficiently.  
✅ **Interactive GUI with Tkinter** – User-friendly interface for component addition and circuit solving.  

---

## **Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/circuit-solver.git
cd circuit-solver
```

### **2. Install Dependencies**  
Ensure you have Python installed (≥ 3.8), then install the required libraries:  
```bash
pip install numpy matplotlib networkx sympy
```

### **3. Run the Application**  
```bash
python circuit_solver.py
```

---

## **Usage Guide**  

### **Adding Components**  
- Select a **component type** (Resistor, Capacitor, Inductor, Switch).  
- Enter the **component value** (Resistance in Ω, Capacitance in F, Inductance in H).  
- Define **start and end nodes** to specify connections.  
- Click **"Add Component"** to add it to the circuit.  

### **Adding a Voltage Source**  
- Enter **amplitude** and **frequency** for AC sources.  
- Select **voltage type** (Sin, Cos, or DC).  
- Define the **starting node** of the voltage source.  
- Click **"Add Voltage Source"** to include it in the circuit.  

### **Solving the Circuit**  
- Click **"Solve Circuit"** to perform **Nodal Analysis** using Laplace Transform.  
- The solution provides **node voltages in both Laplace and time domains**.  
- A **graph of node voltages over time** is displayed for visualization.  

---

## **Example Circuit**  
After adding the following components:  
- **Resistor:** 10Ω between Node 1 and Node 2  
- **Capacitor:** 1µF between Node 2 and GND  
- **Inductor:** 5mH between Node 1 and GND  
- **Voltage Source:** 5V DC at Node 1  

The program will compute and display **time-domain voltage responses** for each node.  

---

## **Future Enhancements**  
📌 Add **support for current sources** in circuit analysis.  
📌 Implement **transient analysis** using numerical methods.  
📌 Improve **UI/UX with drag-and-drop circuit elements**.  
📌 Enable **exporting circuit diagrams as images**.  

---

## **Contributing**  
Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests.  

---
