# Territorial-partitioning-genetic-algorithm
A custom Python-based genetic algorithm designed to solve NP-hard territorial partitioning problems by optimizing demographic balance and geometric compactness under strict spatial connectivity constraints.

![Animation](assets/3_Evolution_Carte.gif)

# Key Features

**Graph-Based Modeling:** Represents territories as dual graphs using NetworkX.

**Connectivity-Aware Operators:** Custom crossover and mutation functions designed to prevent district fragmentation.

**Multi-Objective Optimization:** Balances demographic parity and geometric compactness (Isoperimetric Quotient).

**From Scratch Implementation:** Built without black-box optimization libraries to allow full control over spatial heuristics.

# Tech Stack
**Language:** Python 3.11+

**Libraries:** NetworkX (Graph Theory), Pandas (Data handling), Matplotlib (Visualization).

#  Visual Results

**Final Partitioning Map:**

![Animation](assets/1_Carte_Finale_HD.png)

**Example of the algorithm generating 13 connected and balanced districts:**

![Animation](assets/3_Evolution_Carte.gif)

**Example of the evolution of populations per district:**

![Animation](assets/4_Evolution_Populations.gif)
