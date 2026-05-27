# 📊 Customer Behavior Analysis Dashboard — Power BI

An interactive, end-to-end Power BI dashboard designed to analyze customer purchase behavior, transaction histories, and engagement patterns to unlock actionable business insights and anticipate future needs.

This repository is distributed as a Power BI Template (`.pbit`), allowing users to easily load the provided sample dataset or plug in their own data seamlessly.

---

## 🛠️ Tech Stack & Features

* **Power BI Desktop:** Dashboard design, data modeling, and report authoring.
* **DAX (Data Analysis Expressions):** Advanced calculated measures, KPIs, and time-intelligence functions.
* **Data Sources:** Structured CSV / Excel files.
* **Interactive Elements:** Dynamic cross-filtering, multi-attribute slicers, trends over time, and geographical mapping.

---

## 🚀 Key Functional Features

* **Behavioral Segmentation:** Analyze customer cohorts grouped by purchase frequency, volume, and total order value.
* **Performance Tracking:** Drill down into sales, profit margins, and net results aggregated by product categories and regions.
* **High-Level KPIs:** Instant visibility into core business metrics (Gross Sales, Net Sales, Discounts, Costs, and Final Revenue).
* **Plug-and-Play Architecture:** Easily test the dashboard using the included pre-formatted sample CSV dataset.

---

## 📁 Dataset & Column Schema

The template runs on a sample dataset located in the repository: `dataset/client_behavior_example.csv`. 

> 💡 **Custom Data Integration:** You can easily swap this file out for your own business data. To ensure successful automated data mapping, your data schema must match the following columns:
> `ClientID`, `Client`, `ClientStatus`, `ClientDate`, `VenteDate`, `ClienteleCode`, `ClienteleType`, `City`, `CountryCode`, `Country`, `ArticleID`, `Article`, `GammeID`, `Gamme`, `RemiseCode`, `RemiseType`, `CanalID`, `Canal`, `FabricantID`, `Fabricant`, `CUHT` (Unit Cost Excl. Tax), `VenteNombre` (Quantity Sold), `PUHT` (Unit Price Excl. Tax), `VenteBrut` (Gross Sales), `Remise` (Discount), `VenteNet` (Net Sales), `Cout` (Total Cost), `Resultat` (Net Profit), `DateJourNumero`, `DateJourCourt`, `DateMoisNumero`, `DateMoisNom`, `DateAnneeSemaine`, `DateAnnee`.

---

## ⚙️ Quick Start Guide

Follow these simple steps to run the interactive dashboard locally:

1. **Clone or Download** this repository to your local machine.
2. Locate the **Power BI Template file**: `Analyse_Comportement_Clients.pbit`.
3. Open the file using **Power BI Desktop** (free version available via Microsoft Store).
4. When prompted, browse and select the sample file `dataset/client_behavior_example.csv` (or upload your custom formatted data).
5. Explore the interactive visual charts, filters, and dynamic slicers.

<img width="766" height="770" alt="Capture d’écran 2026-05-27 144117" src="https://github.com/user-attachments/assets/8d3a4943-1552-4e87-b1fd-e1e723ed4266" />


---

## 🔮 Future Roadmap & Improvements

- [ ] **Live Data Integration:** Connect the model directly to a cloud database (SQL Server, Snowflake) for automated schedules and real-time updates.
- [ ] **Advanced Customer Analytics:** Implement predictive behavior metrics using DAX and integrated Python/R scripts for customer churn analysis.
- [ ] **Cloud Deployment:** Publish the dashboard report to **Power BI Service** to showcase workspace sharing, access control, and mobile layouts.
- [ ] **Advanced Visuals:** Add automated cluster analysis (AI-driven segmentation) and geographic heatmaps.
