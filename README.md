# Classifying Outbreak Severity: A Web-Based Simulation Tool

### [View the Full Final Year Project Report (PDF)](Outbreak_Severity_FYP_Report.pdf)

---

## 1. Project Overview

This is my Final Year Project for my BSc in Computing. The goal was to develop a full-stack, interactive web application that allows non-expert users to simulate the spread of an infectious disease through a social network and see a real-time classification of the outbreak's severity.

The project addresses a key gap in public health tools: the lack of accessible, interactive simulators that can help educate the public on epidemiological dynamics.

---

## 2. Key Features & Functionality

*   **Network-Based SEIRSD Simulation:** Models disease spread using a network graph and an extended SEIRSD model (Susceptible-Exposed-Infected-Recovered-Susceptible-Deceased).
*   **Interactive User Interface:** A web-based UI allows users to set all key simulation parameters (e.g., transmission rate, population size) and see the results update dynamically.
*   **Dynamic Visualizations:** Uses Plotly.js to generate interactive charts and network graphs of the outbreak's progression.

---

## 3. Skills & Technologies Used

*   **Backend:** Python, FastAPI
*   **Frontend:** Plotly.js (for interactive visualizations)
*   **Data Science & ML:** Scikit-learn, Pandas, NumPy, Feature Engineering
*   **Project Management:** CRISP-DM (Cross-Industry Standard Process for Data Mining), MoSCoW Prioritization

---

## 4. Methodology & Key Challenge

The entire project was managed using the **CRISP-DM framework**, ensuring a structured approach from business understanding and data preparation to modeling, evaluation, and deployment.

A key challenge was building a reliable severity classifier. Early experiments with overfitted models achieved near-perfect but misleading accuracy. I made a deliberate choice to correct for data leakage and use a robust, time-based split for training. While this resulted in a more realistic **final accuracy of 65%**, it represents a **more trustworthy and generalizable model**, prioritizing real-world performance over inflated metrics—a critical trade-off in responsible data science.

---
