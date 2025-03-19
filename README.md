# Customer Service Scheduling Optimization using Integer Linear Programming

## Introduction

This project applies **Integer Linear Programming (ILP)** to optimize workforce scheduling in a customer service environment. The goal is to determine the optimal number of **Customer Service Representatives (CSR)** needed while ensuring efficient scheduling and minimizing call waiting times. This approach ensures a balance between operational efficiency and employee well-being.

## Objectives

- **Minimize call waiting time** to enhance customer satisfaction.
- **Maximize workforce utilization** by ensuring efficient shift allocations.
- **Ensure fair scheduling** with **two mandatory rest days** per week for each CSR.

## Methodology

This project formulates the scheduling problem as an **Integer Linear Programming (ILP) model**. The constraints and objectives considered include:

- **Minimum and maximum number of CSRs per shift** to meet service demand.
- **Required service levels** to reduce customer wait times.
- **Mandatory two-day rest period** for each employee to prevent burnout.

The model was implemented using **Python** and solved using **PuLP**, a library for linear programming.

## Implementation

### **Tools & Libraries Used:**

- **Python** (Jupyter Notebook)
- **PuLP** (Linear Programming Solver)
- **Matplotlib/Seaborn** (for visualization)

## Results

The ILP model generates an optimized schedule that ensures **adequate staffing**, reduces call waiting times, and maintains fair work-rest distribution. Below are sample visualizations comparing the results **before and after optimization:**

### **1. Staffing Distribution Before vs. After Optimization**

\
This graph compares the staffing levels before and after applying the ILP model. The optimized schedule ensures that shifts have sufficient coverage while avoiding overstaffing.

### **2. Call Waiting Time Reduction**

\
This visualization shows how the ILP model reduces call waiting times by efficiently allocating CSRs to high-demand periods.

### **3. Rest Days Allocation**

\
This graph demonstrates that each CSR is given two mandatory rest days per week, ensuring fairness and preventing burnout.

### **Analysis of the Results**

The visualization presents the optimized staffing schedule, ensuring the balance between **service efficiency and employee well-being**. Key aspects of the results include:

- **Shift Assignments:** Each CSR is assigned to a shift while ensuring compliance with the constraints (minimum staffing levels and required off-days).
- **Waiting Time Reduction:** The model prioritizes allocating CSRs based on predicted call volume trends to minimize customer waiting time.
- **Rest Days Allocation:** Each CSR is guaranteed **two rest days per week**, ensuring fairness and preventing burnout.
- **Workforce Utilization:** The model ensures that no shifts are understaffed while avoiding excessive scheduling that may lead to unnecessary costs.

The scheduling assumptions include:

- **Seven shift per week, that each shift work for five consecutive days.**
-
- **Minimum CSR requirements for each shift based on historical call volume data.**
- **Employees are not allowed to work more than five consecutive days.**

## Conclusion

This project demonstrates how **mathematical optimization** can improve workforce management, ensuring both **service efficiency and employee satisfaction**. The use of **Integer Linear Programming** provides a structured and data-driven approach to scheduling challenges.
