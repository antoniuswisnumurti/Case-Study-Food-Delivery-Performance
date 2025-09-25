🍔 Food Delivery Performance – Zomato (Case Study)

This project analyzes Zomato Delivery Operations data to understand the factors that affect delivery time in metropolitan areas. It includes data preprocessing, exploratory analysis, and interactive visualizations via Streamlit.

📌 Project Overview

Goal: Improve customer satisfaction by reducing delivery times.

Focus: Metropolitan subset of Zomato delivery dataset.

Period: 11 Feb 2022 – 6 Apr 2022

Dataset Size: 45,584 rows × 20 columns (reduced to 35,287 × 22 after cleaning)

Source: Kaggle – Zomato Delivery Operations Analytics

❓ Business Questions

% of completed orders by vehicle?

Average delivery time by vehicle in metropolitan areas?

Which vehicle most often handles multiple orders?

Do traffic, weather, and vehicle condition affect delivery time?

⚙️ Tech Stack

Python: pandas, matplotlib, seaborn

Jupyter Notebook: preprocessing & exploration

📂 Repository Structure
├── Data Exploration.ipynb       # Notebook for cleaning & EDA
├── Dashboard.pbix               # Dashboard PowerBI
├── README.md                    # Project documentation

📊 Key Insights

Motorcycles dominate deliveries (60%).

Scooters & e-scooters are 3 minutes faster on average.

Multiple deliveries raise variance of ETA (1.7–2+ orders/trip).

Bad weather (fog, cloudy) increases delivery time >30 min.

Traffic jams impact motorcycles the most (33.4 min avg).

Vehicle condition matters: good/normal saves 4–5 min vs bad.

✅ Recommendations

Assign motorcycles to long-distance multi-order routes.

Increase scooter/e-scooter share from 8% → 10–15%.

Use weather-aware routing & ETA adjustments.

In high traffic, allocate more scooters/e-scooters.

Maintain fleet in good condition to improve efficiency.

👤 Author
**Antonius Wisnumurti Sulistyanto**  
[LinkedIn](https://www.linkedin.com/in/antonius-wisnumurti-sulistyanto/)  
[Email](mailto:antoniuswisnumurti@gmail.com)
