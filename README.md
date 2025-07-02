# Traffic Pattern Analysis

This project analyzes traffic volume patterns using real-world data collected from road junctions. It identifies peak hours, daily trends, junction-specific load, and compares actual vs. predicted traffic counts using visualizations.

---

## 📂 Dataset Information

- **File:** `traffic.csv`
- **Features:**
  - `ID`: Unique identifier
  - `DateTime`: Timestamp of traffic count
  - `Junction`: Junction number (1–4)
  - `Vehicles`: Number of vehicles detected
  - Extracted: `Hour`, `Day`, `Month`, `Year` for analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

---

## 🔍 Data Preprocessing

- Converted `DateTime` to datetime object
- Extracted temporal features (hour, day, month)
- Grouped data by hour, day, and junction for deeper insights
- Cleaned nulls (if any) and validated data types

---

## 📊 Visualizations

### 1. Average Traffic Volume by Hour  
Displays average vehicle count per hour across all days.  
![Hourly Average](https://github.com/LAXMAN7795/Traffic-Pattern-Analysis/blob/0e99615d13de1063863ca2fc927ba68e2a47cc8d/output/hourly_avg.png)

---

### 2. Traffic Volume Heatmap (Day vs Hour)  
Shows how traffic fluctuates across different days and times.  
![Heatmap](https://github.com/LAXMAN7795/Traffic-Pattern-Analysis/blob/896cc3e4afe2ff2af72f8c9df3aa8a7d5d2ca246/output/heatmap.png)

---

### 3. Total Vehicle Count by Junction  
Compares traffic volumes across the four monitored junctions.  
![Junction Summary](outputs/junction_sum.png)

---

### 4. Daily Traffic Trends  
Visualizes how traffic changes over time.  
![Daily Trends](outputs/daily.png)

---

### 5. Actual vs Predicted Vehicle Count  
Shows model predictions vs real traffic volume for evaluation.  
![Prediction](outputs/actual_vs_predicted.png)

---

## 🔑 Key Insights

- **Evening hours (7 PM – 9 PM)** have the highest traffic.
- **Junction 1** consistently experiences the most traffic load.
- Early morning (3–6 AM) has the least traffic.
- Daily traffic trends show gradual increase over time.
- Model struggles slightly with higher actual values, underpredicting peak traffic.

---

## ✅ Conclusion

This analysis provides valuable insight into when and where traffic congestion occurs. Such findings are crucial for smart city planning, traffic light optimization, and load balancing between junctions.

---

## 🚀 How to Run

1. Clone this repository
2. Place `traffic.csv` in the working directory
3. Run `Traffic_Pattern_Analysis.ipynb` in Jupyter or VS Code

---

## 📁 Project Structure

Traffic_Pattern_Analysis/
│
├── Traffic_Pattern_Analysis.ipynb
├── traffic.csv
├── README.md
└── outputs/
├── hourly_avg.png
├── heatmap.png
├── junction_sum.png
├── daily.png
└── actual_vs_predicted.png

---

## 📬 Contact

**Author:** Laxman S. Gouda  
**Email:** laxman.sg0104@gmail.com
