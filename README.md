# ✈️ Tableau Public: U.S. Flight Performance Analysis & Outsider Identification

## Project Goal and Business Challenge
This project was undertaken for a Ministry of Transport to conduct a comprehensive analysis of all airline flights. The primary objective was to transform raw flight data into an actionable **Tableau Public dashboard** focused on identifying **outsider airports and carriers** based on flight cancellations and delays.

The solution aims to uncover critical patterns and provide the Ministry with data-driven recommendations for operational improvement, such as adjusting flight scheduling buffer times at specific bottleneck airports.

## 🛠️ Key Skills & Tableau Techniques Demonstrated

This dashboard showcases expertise in complex data visualization and data preparation:

* **Data Modeling:** Built a robust data model by physically joining flight, airport, and carrier tables using appropriate keys.
* **UX/UI and Structure:** Designed a highly structured, two-dashboard interface (1200x800) with navigation buttons, adhering to Gestalt principles for visual grouping, color coding, and spacing.
* **Advanced Tableau Features:**
    * Effective use of **Parameters** to toggle displayed data or visualizations (mandatory requirement).
    * Implementation of **Dual Axes** for comparative analysis (e.g., tracking delays vs. cancellations).
    * Advanced Tooltip configuration to ensure full airport/carrier/reason names are available on hover.
    * Development of **Dashboard Actions** for user interaction and detailed drill-down analysis.

## 📈 Dashboard Insights and Required Visualizations

The dashboard provides clear answers to the project's core questions through targeted visualizations:

| Section | Key Metrics & Visualizations | Purpose |
| :--- | :--- | :--- |
| **KPIs** | Total Flights, Total Cancellations, Total Delays, Average Arrival/Departure Delay Minutes. | Provides an immediate high-level performance overview. |
| **Outsider Identification** | Packed Bubble/TreeMap visualizations showing top airports/carriers by number of Delays and Cancellations. | Quickly identifies key entities requiring intervention. |
| **Root Cause Analysis** | Breakdown of Delay/Cancellation Reasons (e.g., Security, Weather, Late Aircraft). | Allows drill-down to understand *why* performance is poor. |
| **Ratios** | Visual display of the ratio of Cancelled/Delayed flights to Total Flights (in various breakdowns). | Contextualizes raw numbers against overall activity. |
| **Timeline** | Monthly or Quarterly dynamics of order/cancellation counts and amounts. | Tracks performance changes over time. |

## 🔗 Live Dashboard & Data Source

The analysis is based on public U.S. flight records data.

* **Live Dashboard Link:** **[INSERT YOUR TABLEAU PUBLIC URL HERE]**
* **Data Source (Optional):** [Include a link to your raw data file, if uploaded to GitHub]

---

## 🖼️ Dashboard Preview

A screenshot of the live dashboard structure and layout:

![Tableau Public Flight Statistics Dashboard](images/flights_statistics_dashboard.jpg)
