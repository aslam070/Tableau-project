# Airlines Fare & Route Analysis (Tableau Project)

## Project Overview

This project analyzes a dataset of **300,000+ flight records** across major Indian cities to uncover insights into airline ticket pricing, route popularity, and operational performance. Using **Tableau**, two interactive dashboards were developed to visualize key trends and provide actionable insights for strategic decision-making in the airline industry.

---

## Objectives

The main objectives of this Tableau project were to:

* Identify popular and high-traffic flight routes within India.
* Compare ticket pricing patterns across different airlines and travel classes (Economy vs. Business).
* Analyze the impact of flight stops on average travel duration.
* Evaluate airline market share based on flight frequency.
* Visualize fare distribution and identify high-cost departure/arrival cities.

---

## Problem Statement

The airline industry operates in a highly competitive environment where pricing, route efficiency, and market share are critical. Stakeholders need clear, data-driven insights to understand:

1.  **Pricing Dynamics:** Which routes and airlines command premium fares? Where are the opportunities for budget options?
2.  **Route Performance:** Which routes are most popular, indicating key travel corridors?
3.  **Operational Efficiency:** How significantly do stops impact travel time for passengers?
4.  **Market Competition:** Which airlines dominate the market in terms of flight volume?

This analysis addresses these questions by providing interactive visualizations of the flight booking data.

---

## Dataset Information

The analysis used a scraped dataset of flight bookings between major Indian cities, sourced from Kaggle.

| Column           | Description                         |
| :--------------- | :---------------------------------- |
| airline          | Airline name                        |
| flight           | Flight number                       |
| source\_city     | Departure city                      |
| departure\_time  | Time of day (categorical)           |
| stops            | Number of stops                     |
| arrival\_time    | Time of arrival (categorical)       |
| destination\_city| Arrival city                        |
| class            | Economy or Business                 |
| duration         | Flight time in hours                |
| days\_left       | Days until departure                |
| price            | Ticket price (₹)                    |

**Dataset Size:** 300,153 records, 12 columns 

---

## Technology Stack

| Component                  | Tool / Language               |
| :------------------------- | :---------------------------- |
| Data Cleaning & Processing | Power Query (Assumed)         |
| Visualization / Dashboard  | Tableau                       |
| Data Source                | Kaggle (CSV)                  |
| Documentation              | Markdown (README), Word       |

---

## Key Insights (from Dashboards)

* **Busiest Route:** Delhi → Mumbai is the most popular route with over 15.3K flights.
* **Market Leaders:** Vistara operates the highest number of flights (approx. 43% market share), followed closely by Air India (approx. 27%).
* **Pricing Tiers:** Vistara consistently shows the highest average fares, especially in Business class (avg. ₹47K) and holds all top 10 most expensive flight records (up to ₹1.23L). AirAsia offers the lowest average Economy fares (avg. ₹5K).
* **High-Fare Cities:** Flights originating from or destined for Kolkata and Mumbai tend to have the highest average ticket prices.
* **Impact of Stops:** Non-stop flights are significantly faster (avg. 2.19 hrs) compared to flights with 1 stop (avg. 13.5 hrs) or 2+ stops (avg. 15.3 hrs).


---

## Recommendations

Based on the analysis, potential strategies for airlines include:

1.  **Dynamic Pricing:** Implement dynamic pricing on high-demand routes like Delhi-Mumbai to maximize revenue.
2.  **Promote Non-Stop Efficiency:** Market the significant time savings of non-stop flights to attract business and time-sensitive travelers.
3.  **Target High-Fare Markets:** Consider introducing competitive budget options or increasing capacity on routes involving Kolkata and Mumbai.
4.  **Premium Service Focus:** Airlines like Vistara and Air India can leverage their market position by enhancing loyalty programs for their premium/business class passengers.

---

## Conclusion

This Tableau analysis provides valuable, interactive insights into India's domestic airline market. The dashboards effectively highlight key trends in pricing, route demand, and operational efficiency, empowering airlines with data to refine their strategies, optimize pricing, and improve competitiveness.
