# AtliQ Hospitality - Revenue Insights Dashboard

## 📊 Project Overview

This project is a comprehensive Power BI dashboard designed to provide deep insights into the revenue and performance of AtliQ Hospitality, a hotel chain. The dashboard helps stakeholders, such as revenue managers and key decision-makers, to understand key metrics, identify trends, and make data-driven decisions to improve market share and revenue.

This end-to-end data analytics project involves:
1.  **Data Cleaning & Transformation** using Power Query.
2.  **Data Modeling** with a Star Schema.
3.  **DAX Calculations** to create complex Key Performance Indicators (KPIs).
4.  **Dashboard Design & Visualization** to present insights effectively.

---

## 🖼️ Dashboard Preview

![AtliQ Hospitality Dashboard](./Revenue%20Insights%20-%20Dashboard.jpg)

---

## 🎯 Problem Statement

AtliQ Hospitality has been losing market share and revenue in recent months. The management lacks a clear, data-driven view of their performance across different properties, cities, and booking platforms. They need a unified dashboard to answer critical business questions like:

- What are the key drivers of revenue?
- Which properties are performing best or worst?
- How is the occupancy rate trending over time?
- What is the impact of different booking platforms on revenue and cancellations?
- How can we optimize pricing and room allocation based on demand?

---

## 🛠️ Tech Stack

* **Microsoft Power BI:** For data modeling, analysis, and visualization.
* **Power Query:** For data extraction, cleaning, and transformation (ETL).
* **DAX (Data Analysis Expressions):** For creating custom measures and KPIs.
* **Data Source:** CSV files.

---

## ⚙️ Project Structure

### Data Model

A robust **Star Schema** data model was implemented to ensure efficiency and scalability.

* **Fact Tables:**
    * `fact_bookings`: Contains transactional data for each booking (booking ID, dates, revenue, platform, etc.).
    * `fact_aggregated_bookings`: Contains aggregated daily data for bookings and capacity.
* **Dimension Tables:**
    * `dim_date`: Contains date-related information (week number, day type, month, etc.).
    * `dim_hotels`: Contains details about each hotel property (name, city, category).
    * `dim_rooms`: Contains details about room categories.

![Data Model Snippet](<img width="1219" height="740" alt="Revenue Insights - Dashboard" src="https://github.com/user-attachments/assets/09e24124-d91c-4e81-9ff8-251faec6e547" />
)
**


### Key Metrics & KPIs

The dashboard focuses on several critical hospitality metrics, including:

- **Total Revenue:** The total income generated from bookings.
- **Occupancy %:** The percentage of available rooms that were occupied. `(Total Booked Rooms / Total Capacity)`
- **ADR (Average Daily Rate):** The average rental income per occupied room per day. `(Total Revenue / Total Booked Rooms)`
- **RevPAR (Revenue Per Available Room):** The most important metric for hotel performance. `(Total Revenue / Total Capacity)`
- **Realisation %:** Percentage of bookings that resulted in a stay.
- **DSRN (Daily Sellable Room Nights):** Total rooms available for sale each day.

---

## 🚀 How to Use

1.  **Prerequisites:** You must have **Microsoft Power BI Desktop** installed.
2.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
3.  **Open the file:** Navigate to the project directory and open the `Revenue Insights in Hospitality Domain.pbix` file in Power BI Desktop.
4.  **Explore:** Interact with the dashboard filters and visuals to explore the data insights.

---

## ✨ Key Insights & Findings

*(This is a great section to summarize what you learned from the data)*

* **Weekend vs. Weekday Performance:** The dashboard reveals a significant difference in occupancy and ADR between weekends and weekdays.
* **Top Performing Properties:** AtliQ Grands in Mumbai consistently generates the highest revenue.
* **Booking Platform Analysis:** Direct bookings have the highest realization rate, suggesting a lower cancellation risk compared to online travel agencies (OTAs).

---

## 👤 Author

* **[Shafaque Jamal Ansari]**
