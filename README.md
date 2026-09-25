# 📊 Superstore Enterprise Performance Dashboard (Power BI)

An end-to-end multi-report Business Intelligence solution built to analyze commercial performance, product profitability, consumer segments, and fulfillment logistical latency across the United States and Canada.

## 🚀 Live Dashboard Preview
* Take screenshots of your 5 beautifully polished pages and drag-and-drop them right here in this section! *

## 🗂️ Dashboard Architecture & Navigation Flow
The report framework consists of **5 interconnected application pages**:
1. **Welcome Hub:** Contextual guide establishing data boundaries and system definitions.
2. **Executive Overview:** Core financial metrics (\$2.33M Total Revenue, 12.6% Profit Margin) featuring seasonal timeline run-rates and geographic footprint mapping.
3. **Product & Merchandising Analytics:** Diagnostic grid separating top revenue drivers from toxic profit drains, featuring an interactive discount-vs-profit scatter chart.
4. **Customer & Regional Insights:** Detailed account leaderboards matched against supply-chain shipping volumes.
5. **Operational Drill-Down Cockpit:** Searchable transaction lookup matrix complete with automated delivery exception tags.

## 🛠️ Data Engineering & Modeling
* **Data Prep (Power Query):** Structured dirty geography variables, configured data types, and constructed custom row-level logistical metrics (`Fulfillment Days`).
* **Star Schema Architecture:** Deconstructed flat source data into distinct dimension tables (`Dim_Customers`, `Dim_Products`) linking dynamically to a quantitative `Fact_Sales` transaction ledger via single-direction relationships.
* **Core DAX Measures Panel:** Developed centralized calculations for revenue generation, distinct order volume tracing, margin efficiencies, and adaptive color metrics for automated visual exceptions.
