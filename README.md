# OPTIMIZATION_MODEL

COMPANY: CODTECH IT SOLUTIONS

NAME: UPASANA PRAJAPATI

INTERN ID: CT08DF387

DOMAIN: DATA SCIENCE

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION OF THE TASK:


---

## 📊 Project: Linear Programming - Production Optimization

This project demonstrates how to apply **Linear Programming** techniques to a **production optimization** problem using Python and matplotlib for visualization.

---

# 🏭 Linear Programming – Production Optimization using Python

This project demonstrates how **Linear Programming (LP)** can be used to optimize production planning and maximize profit subject to resource constraints. The implementation involves visualizing constraint lines, feasible regions, and optimal solutions.

## 📘 Project Overview

The objective is to **maximize profit** by deciding the optimal number of units to produce for two products, A and B, under given constraints (like labor hours, materials, etc.). This project illustrates:

* Formulation of linear constraints and objective function.
* Graphical method to find feasible region and optimal solution.
* Visualization of profit levels and their interaction with constraints.

---

## 🧾 Files Description

### 🔹 `notebook.ipynb`

This Jupyter notebook contains the entire implementation, including:

* Defining constraints
* Plotting constraint lines
* Shading feasible regions
* Plotting profit lines
* Identifying the optimal solution

The code uses `matplotlib`, `numpy`, and LP concepts to visualize and solve the problem graphically.

---


## 📈 Objective Function

Maximize:
**Profit = c₁x + c₂y**,
where `x` and `y` are units of Product A and B respectively, subject to linear constraints.

---

## 🧰 Tools & Libraries Used

* Python 3.x
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 🛠️ Applications

* Manufacturing and Production Planning
* Resource Allocation
* Business Decision Making
* Supply Chain Optimization

---


### 📊 Output Visualizations

---

### 📌 `output1.png`: Constraint Lines

This plot displays the **constraint lines** for the Linear Programming problem:

* Each line represents a constraint such as resource limitations (like labor hours or material).
* The **blue** and **green** lines represent linear inequalities that define the feasible region.
* These lines are the foundation for constructing the feasible solution space.

---

### 📌 `output2.png`: Feasible Region

This figure shows the **feasible region**:

* Formed by overlapping the areas that satisfy all constraints.
* The **shaded area** (in gray) represents the region where all constraints are satisfied.
* Only the points inside this region are considered for optimal solutions.

---

### 📌 `output3.png`: Optimal Solution Point

This image marks the **optimal solution**:

* A **red dot** indicates the point that gives the **maximum profit** or desired objective value.
* This point lies on the boundary of the feasible region where the objective function reaches its optimal value.

---

### 📌 `output4.png`: Profit Lines with Feasible Region

This visualization overlays **profit lines** on top of the feasible region:

* The dashed lines represent different levels of profit (e.g., \$300, \$400, \$500).
* The optimal profit line is marked and aligned with the **red dot** from `output3.png`.
* Clearly shows how moving along the profit lines within the feasible region helps find the best result.

---

## 🔧 Technologies Used

* Python 🐍
* `matplotlib` 📉
* Linear Programming (using `scipy.optimize` or `pulp` for back-end logic)

## 📈 Applications

* Resource allocation
* Profit maximization
* Supply chain & manufacturing decisions

## 📎 How to Run

1. Clone this repository.
2. Open `notebook.ipynb` using Jupyter Notebook.
3. Run the cells to view plots and optimization results.

---


