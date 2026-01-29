

# ✈️ Project 02: 2015 Flight Delays and Cancellations Data Analysis

## 📌 Project Overview

This project focuses on analyzing the **2015 Flight Delays and Cancellations** dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.
The goal is to explore airlines, airports, and flights data through **descriptive analysis and visualizations** to understand patterns related to delays, cancellations, and flight distributions.

---

## 📂 Datasets Used

### 1️⃣ **Airlines Dataset**

**Columns:**

* `Iata Code`
* `Airline`

This dataset provides a mapping between airline names and their IATA codes.

---

### 2️⃣ **Airports Dataset**

**Columns:**

* `Iata Code`
* `Airport`
* `City`
* `State`
* `Country`
* `Latitude`
* `Longitude`

This dataset contains geographical and location-based information about airports.

---

### 3️⃣ **Flights Dataset**

**Columns include:**

* Date information (Year, Month, Day, Day_of_week)
* Airline & Flight details
* Origin & Destination airports
* Departure & Arrival times
* Delay information
* Cancellation status and reasons
* Delay causes (Weather, Airline, Security, etc.)

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Data Cleaning & Inspection

* Checked data types and dataset structure
* Identified missing values
* Checked duplicate rows
* Renamed columns for consistency and readability

---

## 📈 Visualizations & Analysis

## 1️⃣ Airlines Dataset Analysis

### ✔ IATA Code Distribution

* **Visualization:** Countplot
* **Insight:**
  Displays all airline IATA codes. Each code uniquely identifies an airline, so the visualization is mainly for representation.

### ✔ Airline Distribution

* **Visualization:** Countplot
* **Insight:**
  Shows the distribution of airline names in the dataset.

### ✔ Relationship Between IATA Code and Airline

* **Visualization:** Heatmap & Table
* **Insight:**
  The relationship between IATA Code and Airline is **one-to-one**.
  Visualizations are used for clarity rather than statistical correlation.

---

## 2️⃣ Airports Dataset Analysis

### ✔ Airport IATA Codes

* **Visualization:** Countplot
* **Insight:**
  Displays airport IATA codes, most of which are unique.

### ✔ Airports

* **Visualization:** Countplot & Pie Chart
* **Insight:**
  Shows airport distribution and relative proportions.

### ✔ Cities

* **Visualization:** Bar plot (Top 10) & Countplot
* **Insight:**
  Highlights cities with the highest number of airports.

### ✔ States

* **Visualization:** Bar plot (Top 10) & Countplot
* **Insight:**
  Shows which states contain the most airports.

### ✔ Countries

* **Visualization:** Countplot & Pie Chart
* **Insight:**
  Most airports are located in the USA.

### ✔ Latitude & Longitude

* **Visualizations:**
  Histogram, Boxplot, Violin plot, Scatter plot, Hexbin map
* **Insight:**
  Illustrates the geographical distribution, spread, and density of airports.

---

## 3️⃣ Flights Dataset Analysis

### ✔ Flights per Airline

* **Visualization:** Countplot
* **Insight:**
  Shows the number of flights operated by each airline.

### ✔ Flights per Day of Week

* **Visualization:** Countplot
* **Insight:**
  Identifies peak travel days.

### ✔ Top Origin Airports

* **Visualization:** Bar plot
* **Insight:**
  Displays the most active departure airports.

### ✔ Cancelled vs Completed Flights

* **Visualization:** Countplot
* **Insight:**
  Compares cancelled flights to completed ones.

### ✔ Departure & Arrival Delays

* **Visualization:** Histograms
* **Insight:**
  Shows delay distributions and highlights extreme delays.

### ✔ Flight Distance

* **Visualization:** Histogram
* **Insight:**
  Displays how flight distances are distributed.

### ✔ Distance vs Arrival Delay

* **Visualization:** Scatter plot
* **Insight:**
  Explores the relationship between flight distance and arrival delay.

### ✔ Cancellation Reasons

* **Visualization:** Bar plot
* **Insight:**
  Shows the most common reasons for flight cancellations.

### ✔ Delay Causes

* **Visualization:** Bar plot
* **Insight:**
  Compares total delay minutes caused by weather, airline, security, etc.

### ✔ Monthly Analysis

* **Visualizations:**

  * Countplot (Flights per Month)
  * Line plot (Average Arrival Delay per Month)
* **Insight:**
  Identifies seasonal trends and peak delay months.

---

## 📌 Conclusion

Multiple visualization techniques were applied across all datasets to analyze:

* Distribution
* Frequency
* Delay patterns
* Geographical spread

This project provides a comprehensive understanding of flight delays and cancellations in 2015 and highlights key operational and seasonal insights.

---

## 🚀 Future Improvements

* Merge datasets for deeper analysis
* Predict flight delays using machine learning
* Interactive dashboards using Plotly or Power BI

---

