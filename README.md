# ✈️ Indian Flights Booking Dataset Analysis

## 🧠 Overview

This project presents a full end-to-end data analysis of a large flight booking dataset using Python and Jupyter Notebooks. It is designed for data analysts and data science enthusiasts, especially those interested in the aviation or travel industry.

The dataset includes 300,000+ records of flight bookings between various Indian cities, providing comprehensive insights into airline performance, pricing trends, flight timing patterns, and customer behavior. This analysis demonstrates how to clean, explore, and visualize structured data to derive actionable business insights.

---

## 📁 Project Structure
flight-price-analysis/
├── flights_analysis.ipynb         # Main analysis notebook
├── flights.csv                    # Dataset 
├── README.md                      # Project overview and documentation
└── images/                        # Folder for exported charts 


---

## 🔧 Tools & Technologies

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Key Questions Answered

- Which airlines operate the most/least flights?
- What are the peak and off-peak times for flight departures and arrivals?
- How do ticket prices vary by:
  - Airline
  - Cabin class (economy/business)
  - Source and destination cities
  - Booking lead time
  - Flight timings
- What patterns emerge from multi-condition queries?

---

## ✨ Highlights

- ✅ Cleaned and structured a large dataset of 300k+ records
- 🧹 Handled Unicode and missing data issues
- 📈 Performed grouped aggregations and calculated average ticket prices
- 🎯 Used multi-condition filtering to target specific queries
- 📊 Created clear and insightful visualizations:
  - Bar plots
  - Horizontal bar charts
  - Categorical plots
  - Relational line plots

---

## 🔍 Key Insights

- **Airline Distribution**: Vistara dominates with over 120k flights; SpiceJet has the least.
- **Flight Timings**: Morning departures & night arrivals are most common.
- **City Traffic**: Delhi is the top source; Mumbai is the top destination.
- **Ticket Prices**: Vistara is the most expensive; Air Asia is the cheapest on average.
- **Booking Time Impact**: Prices increase sharply when booking close to the flight date.
- **Cabin Class Difference**: Business class is ~8x costlier than economy.
- **Timing Influence on Price**: Night departures and evening arrivals are most expensive.
- **City-wise Price Variation**: Chennai and Kolkata show higher average prices.

---

## 📷 Sample Visualizations

```markdown
![Destination cities vs No. of flights]([Destination cities vs No. of flights.png](https://github.com/kmakgotlho/Indian-Flights-Booking-Dataset-Analysis/blob/af3812961e0004f7db78140202d24ecc0c681e67/Destination%20cities%20vs%20No.%20of%20flights.png))
![Flight Departure Time Distribution](images/departure_time_dist.png)

