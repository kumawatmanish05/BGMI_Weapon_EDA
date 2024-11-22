# 📊 PUBG Weapon Data Analysis - EDA Project

Welcome to the **Exploratory Data Analysis (EDA)** project on PUBG Mobile Weapon Data! This repository dives deep into the arsenal of PUBG Mobile, analyzing weapon statistics to provide actionable insights for gamers looking to dominate the battleground.

---

## 🎯 Objectives

- **Understand the Dataset:** Explore and visualize data related to weapons available in PUBG Mobile.
- **Analyze Weapon Efficiency:** Determine the most effective weapons based on various parameters like damage, range, and firing rate.
- **Optimize Gameplay:** Provide recommendations for selecting the best weapons in different combat scenarios.

---

## 🗂️ Dataset Details

The dataset used in this analysis includes the following columns:

| Column Name            | Description                                                  |
|------------------------|--------------------------------------------------------------|
| `Weapon Name`          | Name of the weapon.                                          |
| `Weapon Type`          | Type/category of the weapon (e.g., AR, SMG, Sniper).         |
| `Bullet Type`          | Type of ammunition used.                                     |
| `Damage`               | Damage dealt by the weapon per shot.                         |
| `Magazine Capacity`    | Maximum number of bullets the weapon can hold.               |
| `Range`                | Effective firing range of the weapon (in meters).            |
| `Bullet Speed`         | Speed of the bullet when fired.                              |
| `Rate of Fire`         | Number of rounds fired per second.                           |
| `Shots to Kill (Chest)`| Shots required to eliminate an enemy with chest hits.        |
| `Shots to Kill (Head)` | Shots required to eliminate an enemy with head hits.         |

---

## 🔍 Analysis Performed

1. **Damage Distribution:** Identified weapons with the highest and lowest damage stats.
2. **Weapon Type Analysis:** Compared weapon performance across categories (e.g., AR, SMG, Sniper).
3. **Ammunition Insights:** Evaluated efficiency based on bullet type and speed.
4. **Combat Scenarios:** Analyzed performance for short-range, mid-range, and long-range combat.
5. **Kill Efficiency:** Compared weapons based on the number of shots needed for a kill.

---

## 📈 Key Insights

- **Top Damage Dealer:** The sniper rifles dominate in terms of damage per shot, making them ideal for long-range combat.
- **Fastest Kill Weapon:** SMGs with high firing rates and low shots-to-kill stats are deadly in close-quarters combat.
- **Ammunition Matters:** Bullet speed significantly impacts performance in dynamic combat scenarios.
- **Versatility Winner:** Certain assault rifles strike a balance between damage, range, and rate of fire, making them versatile across various situations.

---

## 📌 Notable Visualizations

1. **Weapon Type vs Damage:** A bar chart showcasing the average damage per weapon type.
2. **Range vs Bullet Speed:** A scatter plot visualizing the relationship between range and bullet speed.
3. **Rate of Fire vs Kill Shots:** A heatmap highlighting the correlation between firing rate and kill efficiency.
4. **Magazine Capacity Analysis:** A pie chart comparing the average magazine size across weapon categories.

---

## 🔗 Key Learnings for Gamers

- **Snipers:** Best for players who prefer long-range precision.
- **SMGs:** Ideal for aggressive, close-range engagements.
- **ARs:** A jack-of-all-trades for diverse combat scenarios.
- **Shotguns:** Exceptional in very close combat but limited in versatility.

---

## 📁 Repository Structure

```plaintext
📂 PUBG-Weapon-EDA
├── 📁 data
│   └── pubg_weapon_data.csv      # Dataset used for analysis
├── 📁 notebooks
│   └── pubg_weapon_eda.ipynb     # Jupyter Notebook containing the EDA
├── 📂 visuals
│   ├── damage_distribution.png   # Damage distribution chart
│   ├── range_vs_speed.png        # Scatter plot for range and speed
│   └── rate_of_fire_heatmap.png  # Heatmap for firing rate and kill shots
├── 📄 README.md                  # Project documentation
└── 📄 requirements.txt           # Python libraries required for the project


