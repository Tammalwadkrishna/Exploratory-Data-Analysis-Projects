## 🏏 IPL Player Performance Analysis (2015–2024)

### 📘 Overview  
This project performs a detailed analysis of **IPL player performance** across **10 seasons (2015–2024)**.  
Using Python and NumPy, the project compares multiple players’ **salaries**, **games played**, and **points earned** over the years to understand trends in performance and compensation.

---

### 🎯 Objectives
- Analyze player salary progression across IPL seasons.  
- Compare games played and total points for each player.  
- Store and manage performance data using NumPy arrays.  
- Enable statistical or visualization-based insights into player consistency and growth.

---

### 👥 Players Included
| Player | |
|--------|-------------|
| Sachin | Rahul |
| Smith | Sami |
| Pollard | Morris |
| Samson | Dhoni |
| Kohli | Sky |

---

### 📆 Seasons Covered
`2015, 2016, 2017, 2018, 2019, 2020, 2021, 2022, 2023, 2024`

---

### 🧮 Data Overview

| Category | Description |
|-----------|--------------|
| **Salary Data** | Player salary over 10 IPL seasons (in INR) |
| **Games Played** | Number of matches played each season |
| **Points** | Total performance points earned each year |

Each dataset is stored as a **NumPy array**, making it easy to perform vectorized computations and comparisons.

---

### 🧰 Technologies Used
- **Python 3.x**
- **NumPy** (for numerical computation)
- **Matplotlib** *(for visualization)*
- *(Optional)* Pandas / Seaborn (for advanced analytics)

---

### 📂 Project Structure
```
IPL Project/
│
├── IPL project.ipynb   # Jupyter Notebook with analysis
├── README.md            # Project documentation (this file)
└── data/                # (optional) dataset folder for extensions
```

---

### 📊 Sample Output & Graph

You can visualize salary or performance trends using **Matplotlib**.

#### 👉 Example 1: Plot Salary Growth for a Player
```python
import matplotlib.pyplot as plt
import numpy as np

# Example: Sachin's Salary Trend
Seasons = ["2015","2016","2017","2018","2019","2020","2021","2022","2023","2024"]
Sachin_Salary = [15946875,17718750,19490625,21262500,23034375,24806250,25244493,27849149,30453805,23500000]

plt.figure(figsize=(8,4))
plt.plot(Seasons, Sachin_Salary, marker='o', color='blue', linewidth=2)
plt.title("Sachin Salary Trend (2015–2024)")
plt.xlabel("Seasons")
plt.ylabel("Salary (INR)")
plt.grid(True)
plt.show()
```

#### 👉 Example 2: Compare Salaries of All Players
```python
Players = ["Sachin","Rahul","Smith","Sami","Pollard","Morris","Samson","Dhoni","Kohli","Sky"]
Avg_Salary = Salary.mean(axis=1)  # Average salary for each player

plt.figure(figsize=(10,5))
plt.bar(Players, Avg_Salary, color='orange')
plt.title("Average Salary Comparison (2015–2024)")
plt.xlabel("Players")
plt.ylabel("Average Salary (INR)")
plt.xticks(rotation=45)
plt.show()
```

#### 👉 Example 3: Points vs Games Scatter Plot
```python
player_index = 8  # Example: Kohli
plt.scatter(Games[player_index], Points[player_index], color='green')
plt.title(f"{Players[player_index]} - Points vs Games (2015–2024)")
plt.xlabel("Games Played")
plt.ylabel("Points Scored")
plt.show()
```

These plots help visualize trends, consistency, and correlations among players across different IPL seasons.

---

### 🚀 Future Enhancements
- Add team-wise comparison and statistics  
- Introduce Pandas for easier data manipulation  
- Predict player performance using regression models  
- Build an interactive dashboard (e.g., Streamlit)

---

### 👨‍💻 Author
**Krishna Tammalwad**  
Aspiring AI/ML Engineer | Data Analyst | Python Developer  
  
