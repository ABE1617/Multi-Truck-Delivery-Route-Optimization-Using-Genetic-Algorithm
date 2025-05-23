# 🚚 Multi-Truck Route Optimization Using Genetic Algorithm

This project explores a genetic algorithm-based solution for optimizing delivery routes across multiple cities using several trucks. It simulates city coordinates, generates a distance matrix, and applies evolutionary strategies to minimize total travel cost.

## 🧠 Objective

To design and implement a scalable algorithm that finds efficient delivery routes for multiple trucks across a randomly generated map of cities—minimizing total travel distance and demonstrating the effectiveness of heuristic-based problem solving.

## 💡 What I Built

- Developed a **Genetic Algorithm** from scratch for multi-truck route planning
- Simulated city coordinate data and computed real-time distance matrices
- Visualized logistics data using **Seaborn** and **Matplotlib** for better interpretability
- Implemented a fitness-based evolution strategy with custom mutation and crossover logic
- Fine-tuned algorithm parameters to optimize convergence speed and solution quality

## ⚙️ Key Parameters

The model allows full control over simulation settings:

```python
POPULATION_SIZE = 100
NUM_GENERATIONS = 100
CITY_COUNT = 10
TRUCK_COUNT = 5
Mutation_probability = 0.01
```
---

📊 Visual Insights
Included heatmap visualizations for city distances and route efficiencies to help interpret the algorithm's behavior and progression across generations.
---
🛠 Tech Stack
Python – Core implementation

NumPy – Data handling and distance calculations

Matplotlib & Seaborn – Visual analytics

NetworkX – Graph-based representations of city networks

🚀 How to Run
Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
Install required libraries:
```bash
pip install -r requirements.txt
```
Run the notebook:
```bash
jupyter notebook ALGO_G2_SEMI_Final_ABE.ipynb
```
---
🏁 Results
Successfully demonstrated a scalable approach to vehicle routing problems using evolutionary algorithms—highlighting both the flexibility of heuristic methods and the power of data visualization for logistics optimization.
