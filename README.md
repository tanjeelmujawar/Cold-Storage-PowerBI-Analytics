# Cold Storage Power BI Analytics

An interactive Power BI portfolio project for exploring cold-storage operations: inventory, chamber capacity, energy use, customer activity, and internal stock movement.

> **Portfolio note:** This project uses a synthetic Excel dataset created for demonstration and learning. It does not represent real clients, operational results, or verified cost/energy savings.

## Overview

Cold-storage operations depend on keeping product inventory available while managing chamber space, transfers, and electricity consumption. This report brings those operational views into one Power BI experience, making it easier to examine current stock, capacity utilization, energy usage, and movement patterns across the facility.

The completed report includes KPI cards, interactive visuals, slicers, bookmarks, and a connected data model. Advanced chamber-consolidation and energy-optimization analysis is currently in progress.

## Tools Used

- **Power BI Desktop** — data modeling, DAX measures, visuals, bookmarks, and report design
- **Microsoft Excel** — synthetic source data
- **Power Query** — data preparation and transformation
- **DAX** — calculated measures and KPI logic

## Dataset

The source workbook is a synthetic operational dataset designed to simulate a cold-storage facility.

| Item | Details |
| --- | --- |
| Data source | Synthetic Excel workbook |
| Operational tables | 21 |
| Total records | 6,043 |
| Reporting period | September 1–October 20, 2026 |
| Customers | 40 |
| Products | 11 |
| Storage chambers | 12 |

## Dashboard Features

- Executive KPI cards for stock, utilization, energy consumption, and transfers
- Chamber-level capacity and utilization analysis
- Inventory views by customer, product, and chamber
- Energy-consumption trends and operational comparisons
- Stock-transfer tracking across storage locations
- Interactive slicers for focused exploration
- Bookmarks to support guided report navigation
- Defined table relationships for consistent cross-filtering

## Current KPI Snapshot

The latest project snapshot reports:

| KPI | Value |
| --- | ---: |
| Current stock | 464,700 kg |
| Capacity utilization | 48.92% |
| Energy consumption | 79,470.49 kWh |
| Stock transfers | 117 |

These figures are calculated from the synthetic project data for the stated reporting period and are intended for demonstration only.

## Data Model

The model connects operational tables covering inventory, products, customers, storage chambers, energy, and stock transfers. Relationships enable the report to filter and compare measures consistently across operational dimensions.

Key areas modeled include:

- **Inventory:** current stock quantity and location
- **Chambers:** available capacity and utilization
- **Energy:** consumption by operational context and time
- **Transfers:** movement of stock between chambers or locations
- **Customers and products:** demand and stock composition analysis

## Insights Supported

The dashboard is designed to help explore questions such as:

- Which chambers have the highest or lowest utilization?
- How is inventory distributed by product and customer?
- When and where are stock transfers occurring?
- How does energy consumption vary over the reporting period?
- Which areas may warrant further review for capacity balancing?

## Work in Progress

Advanced analysis for **chamber consolidation** and **energy optimization** is in progress. The planned work will evaluate operational scenarios and trade-offs; it is not yet a validated recommendation and does not claim verified savings.

## Getting Started

1. Download or clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. If prompted, update the Excel source path in Power Query.
4. Refresh the data.
5. Use slicers and bookmarks to explore the report pages and KPIs.

## Repository Structure

```text
.
├── Cold Storage Analytics.pbix     # Power BI report (add when ready)
├── data/
│   └── cold_storage_data.xlsx      # Synthetic source workbook (optional)
├── images/
│   ├── overview.png                # Screenshot placeholder
│   ├── inventory.png               # Screenshot placeholder
│   └── energy.png                  # Screenshot placeholder
└── README.md
```



## Author

**Tanjeel Mujawar**  
Power BI Analytics Portfolio Project

---

If this project is useful, consider starring the repository or sharing feedback.
