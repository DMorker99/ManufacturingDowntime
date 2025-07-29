# Manufacturing Downtime Analysis - Power BI Project
This Power BI dashboard analyzes job performance across four manufacturing operators highlighting factors influencing downtime, including job start time, product types, and job duration.

## Key Features
- Downtime patterns by time of day
- Highlight downtime issues split by Operator and Non Operator fault
- Operator performance comparisons
- Dynamic filtering with field parameters
- Trendline analysis of downtime over time

## Dataset

Simulated dataset containing:
- publicdowntimefactor: Description, Factorcode, Operatorerror
- publiclinedowntime: Batchid, Downtime, Downtimefactor
- publiclineproductivity: Batch, Date, Starttime, Endtime, Operator, Product
- publicproducts: Product, Flavour, Size, Minbatchtime

## How to Use

1. Download and open `ManufacturingDowntime.pbix` using Power BI Desktop
2. Use slicers to explore:
   - Downtime by time
   - Hour of day performance
   - Operator KPI
   - Operator-specific trends

## Tools & Skills

- Power BI Desktop
- DAX Measures (e.g., downtime %, avg duration)
- Field Parameters & Bookmarks
- Data modeling

## Next Steps
- Use Pandas to model correlation between different downtime factors and operator
- Predictive model to create shift patterns/to assign operator to certain products to reduce downtime (may require more data as very small dataset)
