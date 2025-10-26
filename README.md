
# ✈️ Visualization of Flight Delays in the USA

This project visualizes **flight delay and cancellation trends in the United States** using data from the **U.S. Bureau of Transportation Statistics (2015)**. The goal is to help travelers plan smarter trips by understanding when, where, and why flight delays occur — and which airlines perform better.

---

## 📊 Project Overview

Thousands of flights across the U.S. experience delays or cancellations each year.  
This project explores patterns and trends using **data visualization techniques** such as bar charts, line plots, and geographic heatmaps.

The visualizations aim to answer:
- Which airlines have the most and least delays?
- Which months experience the highest number of delays?
- What are the major causes of flight cancellations?
- Which airports and states face the most disruptions?

---

## 🧠 Motivation

Our motivation stemmed from experiencing flight delays firsthand at JFK Airport.  
We realized that many passengers could benefit from predictive visualizations based on historical delay and cancellation data.

---

## 🗂️ Dataset

The dataset is sourced from the **U.S. Bureau of Transportation Statistics (2015)** and available on Kaggle:

- Dataset Author: GAOFENG HUANG (2019)  
- [View Dataset on Kaggle](https://www.kaggle.com/code/together/visualization-flight-delays/data)

### Files Used:
- `airlines.csv`
- `airports.csv`
- `flights.csv`

Each dataset includes columns such as:
- **Airline, Airport, Month, Departure Delay, Arrival Delay, Cancellation Reason, Delay Type, etc.**

---

## 🧩 Visualizations Implemented

### 1. **Average Delay per Airline**
Bar plot comparing average **arrival and departure delays** for major airlines.

### 2. **Monthly Delay Trends**
Interactive line chart showing monthly delay patterns for each airline, with hover features and color highlights.

### 3. **Airport Delay Map**
Scatter plot and heat map visualizing **average delays and fraction of delayed flights** by airport across the U.S.

### 4. **Cancellations per Airline**
Bar plot showing average flight cancellations by airline.

### 5. **Delay Reasons per Airline**
Bar plot showing number of delays per **cause** (Weather, Security, Airline, Aircraft, Air System).

---

## 🧮 Tools and Technologies

| Tool | Purpose |
|------|----------|
| Python | Data cleaning and processing |
| Pandas | Data manipulation |
| Plotly | Interactive visualizations |
| Matplotlib / Seaborn | Statistical plots |
| Jupyter Notebook | Development environment |

---

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/flight-delays-usa-visualization.git
   cd flight-delays-usa-visualization
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/project_code.ipynb
   ```

4. Follow the notebook cells to view the visualizations interactively.

---

## 🧾 Results and Insights

- Airlines with the **lowest delay times**: *[e.g., Virgin America, Southwest Airlines]*  
- Airlines with **frequent cancellations**: *[e.g., American Airlines, Delta]*  
- Weather and air system issues are among the **top causes** of delay.  
- Some airports consistently show higher delay averages (e.g., JFK, ORD).  

---

## 🚀 Future Work

- Use **multi-year datasets (2013–2022)** for more comprehensive analysis.
- Integrate **machine learning models** to predict future flight delays.
- Develop a **web dashboard** for interactive visualization.

---

## 👨‍💻 Team Members

- **Manasa Gudise**  
- **Prathima Godha**  
- **Vikranth Nallapuneni**

---

## 🧾 License

This project is licensed under the **MIT License** – you’re free to use, modify, and distribute it with attribution.

---

## 📎 References

- [U.S. Bureau of Transportation Statistics](https://www.transtats.bts.gov/)
- [Kaggle: Visualization of Flight Delays](https://www.kaggle.com/code/together/visualization-flight-delays)
- Related research visualizations from Plotly, LinkedIn, and GitHub.
