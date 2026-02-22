# Solar Power Plant Performance Analytics (Power BI)

## Overview

This project presents a multi-page Power BI dashboard designed to monitor and analyze solar power plant performance using inverter-level generation data and weather sensor telemetry.
The solution simulates a SCADA-style monitoring system and enables executive reporting, operational diagnostics, and inverter-level investigation.
Report preview images are available in the **“Report Previews”** folder.

---

## Business Objective

To design a data-driven monitoring system capable of:

* Identifying underperforming inverters
* Analyzing irradiation vs energy output
* Detecting temperature-driven efficiency losses
* Monitoring performance ratio trends
* Supporting maintenance recommendations

---

## Data Model

* Star schema architecture
* Date dimension table
* Generation fact table
* Sensor fact table
* Inverter-level granularity
* Daily aggregation using DAX

---

## Dashboard Structure

### Executive Overview

High-level plant KPIs and energy trends:

* Total energy generated
* Overall inverter efficiency
* Performance ratio
* Module temperature
* Daily energy trend
* Irradiation vs output comparison

### Inverter Analytics

Operational performance analysis:

* Energy per inverter ranking
* Efficiency comparison
* Fault indicators
* Irradiation vs power scatter analysis
* Plant-level filtering

### Performance Diagnostics

Root-cause investigation:

* Temperature vs energy relationship
* Efficiency trend
* PR trend
* Thermal impact analysis
* Dynamic operational insight logic

### Inverter Deep Dive

Drill-through investigation page:

* Hourly power curve
* Daily energy pattern
* Inverter efficiency trend
* Temperature sensitivity analysis

### Executive Summary

Decision-ready summary:

* Average inverter efficiency
* Total energy output
* Performance ratio
* Top performing inverter
* Automated executive insight

---

## Key DAX Measures

* Total AC Power
* Daily Energy (kWh)
* Overall Inverter Efficiency
* Performance Ratio (Proxy)
* Temperature Differential
* Inverter Efficiency Trend
* Top Inverter Identification
* Dynamic Insight Logic

---

## Tools Used

* Power BI Desktop
* DAX
* Power Query
* Star Schema Data Modeling

---

## Dataset

Solar Power Generation Dataset
Source: Kaggle

---

## Project Highlights

* Built a structured star-schema data model
* Implemented advanced DAX-based KPIs
* Designed drill-through diagnostic workflow
* Developed condition-based automated insights
* Created an executive-ready multi-page analytics system

This one is solid. Now we position it strategically.
