# Exploratory-Data-Analysis-Airbnb
Analyzed the Airbnb NYC 2019 dataset (48,895 listings) to uncover insights on pricing trends, neighborhood distribution, host activity, and customer engagement. Identified key patterns in borough-wise pricing, room types, and review behavior to support data-driven decisions for hosts, travelers, and policymakers.

---

# 📌 Project Title:

Airbnb NYC 2019 Data Analysis using Python

---

# 💡 Brief One Line Summary:

Performed data cleaning and exploratory data analysis on Airbnb NYC 2019 dataset to uncover pricing trends, neighborhood patterns, and host performance insights for data-driven decision making.

---

# 🧾 Overview:

This project involved analyzing Airbnb listing data for New York City (2019) to understand pricing distribution, room type trends, availability patterns, and customer engagement. The dataset contained nearly 49,000 listings across five boroughs.

The objective was to transform raw listing data into structured insights that can help hosts optimize pricing, travelers make informed booking decisions, and policymakers assess short-term rental trends.

---

# ❓ Problem Statement:

Airbnb listings vary significantly across boroughs in terms of pricing, availability, room types, and review activity. The dataset also contained missing values and pricing outliers.

The challenge was to:

* Clean and preprocess missing data
* Analyze borough-wise pricing differences
* Study room type pricing impact
* Identify high-performing hosts and listings
* Extract meaningful insights from review and availability trends

---

# 📂 Dataset:

File: AB_NYC_2019.csv

Fields include:
id, name, host_id, host_name, neighbourhood_group, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, reviews_per_month, calculated_host_listings_count, availability_365

Total Records: 48,895
Total Columns: 16

---

# 🛠 Tools and Technologies:

Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Environment: Jupyter Notebook / Google Colab
Data Handling: Data Cleaning, EDA, Aggregation, Visualization

---

# ⚙️ Methods:

### Data Cleaning:

* Replaced missing values in name and host_name with "Unknown"
* Filled missing reviews_per_month with 0
* Replaced missing last_review with "No Review"
* Checked and confirmed no duplicate records
* Identified pricing outliers

### Exploratory Data Analysis:

* Analyzed listing distribution across boroughs
* Compared room types and their pricing patterns
* Studied availability trends across locations
* Evaluated review frequency and host activity

### Feature Insights:

* Compared average price by neighbourhood_group
* Examined relationship between room type and pricing
* Identified high-demand areas using reviews_per_month
* Analyzed listings with zero reviews

---

# 🔍 Key Insights:

* Manhattan and Brooklyn dominate in listing count and demand.
* Entire homes/apartments are significantly more expensive than private or shared rooms.
* Manhattan has the highest average listing price.
* Many listings have zero reviews, indicating inactive or new properties.
* Listings with frequent monthly reviews tend to be competitively priced and centrally located.

---

# 📊 Dashboard / Output:

* Borough-wise price comparison charts
* Room type pricing distribution plots
* Review frequency analysis
* Availability trend visualizations
* Summary statistics tables
  

# ▶️ How to Run this Project?

1. Load AB_NYC_2019.csv into Jupyter Notebook / Google Colab
2. Install required libraries (pandas, numpy, matplotlib, seaborn)
3. Run the data cleaning and EDA scripts
4. Generate visualizations and insights

---

# 📈 Results & Conclusion:

This project demonstrates how Python can be used for:

* Cleaning large real-world datasets
* Performing structured exploratory data analysis
* Identifying pricing and demand trends
* Generating actionable business insights


