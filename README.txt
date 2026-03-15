# Smart Device Market Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset of smart wearable devices such as **smartwatches and fitness bands**.
The goal is to analyze **pricing strategies, brand positioning, product features, and customer perception** using Python libraries like **Pandas, Matplotlib, and Seaborn**.

The analysis focuses on identifying patterns in **price, ratings, battery life, display technology, and brand popularity** to better understand the wearable device market.

---

# Dataset Features

The dataset contains the following key attributes:

* **Brand Name**
* **Device Type**
* **Original Price**
* **Selling Price**
* **Discount**
* **Rating**
* **Reviews**
* **Display Type**
* **Average Battery Life**
* **Strap Material**
* **Color**

---

# 1. Price & Value Analysis

These analyses explore how different brands position their products in the market.

### Discounting Trends

* What is the **average discount percentage across different brands**?
* Which brands **consistently offer the highest discounts**?

### Price vs Rating

* Is there a **correlation between Selling Price and Rating**?
* Do **more expensive devices receive better consumer ratings**?

### The Luxury Segment

* Which **brand has the highest average Original Price**?
* What is the **distribution of Device Types** for premium brands?

---

# 2. Performance & Features

These analyses focus on the relationship between **technical specifications and user satisfaction**.

### Battery Life Distribution

* What is the **most common Average Battery Life** among devices?
* Are there any **extreme outliers** (e.g., devices lasting 30 days vs. 1 day)?

### Strap Material Preferences

* Does **Strap Material influence user Rating**?
* Do premium materials such as **Leather receive higher ratings than Silicone**?

### Display Impact

* How does **Display Type (AMOLED vs LCD)** affect:

  * **Selling Price**
  * **Average Battery Life**

---

# 3. Brand & Market Insights

These analyses examine brand dominance and consumer trends.

### Brand Popularity

* Which **brand has the highest number of reviews**?
* Does **higher review volume correlate with higher ratings**?

### Color Variety

* Which **color is most common across devices**?
* Do specific colors (such as **Gold or Black**) command **higher prices**?

### Device Type Breakdown

* What is the **ratio of Smartwatches to Fitness Bands** in the dataset?

---

# 4. Data Quality & Distribution (Data Health Check)

These checks help understand the structure and reliability of the dataset.

### Price Skewness

* Is the **Selling Price normally distributed**?
* Or is it **skewed toward budget-friendly devices**?

Understanding this helps identify:

* Market pricing structure
* Presence of luxury outliers

---

# Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Key Insights (Example Findings)

* Smartwatches dominate the dataset compared to fitness bands.
* Selling prices tend to be **positively skewed**, indicating more budget devices than luxury models.
* Premium display technologies such as **AMOLED** often correlate with higher prices.
* Some brands offer significantly **higher discounts**, indicating aggressive pricing strategies.

---

# Project Structure

```
Smart-Device-EDA/
│
├── data/
│   └── Fitness_trackers.csv
│
├── notebooks/
│   └── EDAFitBandSmartWatch.ipynb
│
├── images/
│   └── visualizations
│
└── README.md
```

---

# Future Improvements

* Build **interactive dashboards using Plotly or Power BI**
* Perform **machine learning to predict device ratings**
* Conduct **sentiment analysis on customer reviews**

---

# Author

**Vaibhav Patel**
Master's Student – Computer Science
Wright State University
