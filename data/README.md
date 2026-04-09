# Formula 1 Dataset

This folder contains the raw CSV data files used in the Power BI dashboard.

## Data Files

### Core Tables
1. **circuits.csv** (10 KB) - Circuit information (tracks, locations)
2. **constructors.csv** (17 KB) - Team/constructor details
3. **drivers.csv** (94 KB) - Driver information and biographical data
4. **races.csv** (164 KB) - Race calendar and event details
5. **seasons.csv** (5 KB) - Season information

### Results & Performance
6. **results.csv** (1.7 MB) - Race results and finishing positions
7. **qualifying.csv** (453 KB) - Qualifying session results
8. **sprint_results.csv** (21 KB) - Sprint race results
9. **lap_times.csv** (17.2 MB) - Individual lap times (largest file)
10. **pit_stops.csv** (428 KB) - Pit stop data

### Championships & Standings
11. **driver_standings.csv** (877 KB) - Driver championship points
12. **constructor_standings.csv** (314 KB) - Constructor championship points
13. **constructor_results.csv** (217 KB) - Team race results

### Reference Data
14. **status.csv** (2 KB) - Race finish status codes (DNF, Retired, etc.)

## Data Statistics

- **Total Size:** ~21 MB
- **Date Range:** Historical F1 data (1950-2024)
- **Source:** Kaggle Formula 1 Dataset
- **Last Updated:** July 2024

## Data Relationships

```
circuits ←→ races ←→ results ←→ drivers
                 ←→ qualifying
                 ←→ lap_times
                 ←→ pit_stops
                 ←→ sprint_results

constructors ←→ constructor_results
           ←→ constructor_standings
           ←→ results

drivers ←→ driver_standings
       ←→ results
```

## Notes

- All dates are in ISO format (YYYY-MM-DD)
- Times are in milliseconds or HH:MM:SS format
- Missing values may be represented as NULL or \N
- Some older races may have incomplete data

## Usage in Power BI

These CSV files are imported into Power BI Desktop as data sources. The relationships are established in the Power BI data model to enable cross-table analysis.

To refresh data in the dashboard:
1. Open the .pbix file
2. Home → Transform Data
3. Update file paths if needed
4. Close & Apply

---

**Data Source:** Kaggle - Formula 1 World Championship (1950-2024)  
**License:** Public domain / Open data
