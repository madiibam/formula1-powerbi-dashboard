# Formula 1 Power BI Dashboard

An interactive Power BI dashboard for comprehensive Formula 1 analytics and data visualization.

**Author:** Madiyar Mukaram

## Project Overview

This Power BI project provides in-depth analysis and visualization of Formula 1 data, featuring:

- **Driver Performance Analytics** - Individual driver statistics, rankings, and historical performance
- **Constructor Championship Tracking** - Team standings, points progression, and comparisons
- **Race & Circuit Analysis** - Detailed race results, circuit statistics, and geographical insights
- **Interactive Filtering** - Dynamic slicers and drill-through capabilities for custom analysis

## Dashboard Features

### Navigation System
**Left-Side Menu Panel:**
- Clear All Filters button - Reset all applied filters instantly
- Filters panel - Access to comprehensive filtering options
- Page Navigator - Quick navigation between dashboard pages
- Back button - Return to previous page
- Information button - Access page-specific help and details

### Main Pages (14 total)

**1. Formula 1 Overview** (35 visualizations)
Main landing page featuring:
- Total Races: 1,125
- Total Drivers: 859
- Top 5 Drivers ranking with horizontal bar chart
- Global race location map with geographical distribution
- Dynamic points trend line (1950-2024)
- Top Constructors donut chart (Ferrari, McLaren, Mercedes)
- Interactive year slider (1950-2024)
- Constructor and Driver filter dropdowns
- Race Circuit filter dropdown

**2. Driver Performance** (47 visualizations)
Comprehensive driver analytics with:
- Top 5 driver portraits with team photos
- Driver Points by Season - area chart showing historical performance
- Winner Analysis by Starting Position - line chart
- Podium & Wins comparison bar chart
- Total Wins: 9,447
- Average Lap Time: 95.81 seconds
- Detailed driver table with forename, surname, and nationality
- Interactive driver photo tooltips - Click on any driver photo to see:
  - Birth date
  - Current team
  - Total wins
  - Podium count
  - Career points
  - Fastest laps
  - Last win details

**3. Constructor Insights** (34 visualizations)
Team performance analysis:
- Total Constructors: 212
- Constructor ranking table with nationality and total wins
- Podium & Wins distribution - donut chart by team
- Points for Every Constructor - donut chart showing points distribution
- Driver Points by Season - column chart (2016-2024)
- Wins Count Analysis by Position - line chart showing win probability
- Team car images (Ferrari, McLaren, Mercedes)

**4. Races & Circuits** (32 visualizations)
Race and circuit analysis featuring:
- Total Circuits: 3,071
- Total Races: 1,125
- Average Pit Stops: 1.78
- Interactive global map showing races by location
- Top Tracks by Number of Races Held - bar chart
- Dynamics of Races by Year - area chart (1950-2024)
- Best Circuits for Constructors - horizontal bar chart
- Drill-through capability - Right-click on year to access detailed yearly analysis

**5. Drill-through Page: Races & Circuits by Year**
Detailed year-specific analysis:
- Selected year display (e.g., "You select a year: 1993")
- Total Races for selected year
- Count of Circuits used
- Races by Location - regional map with highlighted areas
- Races for Each Quarter - column chart
- Races Count and Total Drivers by Year - donut chart
- Total Races and Total Points by Year - stacked bar chart

**6-13. TT1-TT9** (2-3 visualizations each)
Specialized analytical pages for advanced metrics and custom views

### Interactive Features

**Dynamic Filtering:**
- Year range slider (1950-2024) - Filter all visualizations by time period
- Constructor dropdown - Filter by specific teams
- Driver dropdown - Filter by individual drivers
- Race Circuit dropdown - Filter by track locations
- Clear All Filters button - One-click reset of all applied filters

**Tooltips:**
Hover over any data point to see contextual information:
- Driver photos display detailed statistics on click
- Chart elements show exact values and percentages
- Map regions display race counts and locations
- Bar charts reveal specific data points

**Drill-through Functionality:**
Right-click on any year in the "Dynamics of Races by Year" chart to access:
- Detailed breakdown of that specific season
- Quarterly race distribution
- Circuit usage statistics
- Driver participation data
- Regional race analysis with map

**Cross-filtering:**
Click on any visual element to filter related charts:
- Select a driver to see their specific performance
- Choose a team to view constructor-specific data
- Pick a region on the map to filter by geography

### Visual Elements
- 50 Interactive Buttons - Navigation and filter controls
- 32 KPI Cards - Key performance indicators
- 31 Shapes & Images - Team logos, driver photos, car images
- 20 Slicers - Dynamic data filters
- Multiple Chart Types:
  - Line Charts: 3 (trend analysis)
  - Donut Charts: 3 (distribution analysis)
  - Bar Charts: 2 (comparisons)
  - Area Charts: 2 (historical trends)
  - Column Charts: 2 (categorical data)
  - Pie Chart: 1 (proportional data)
  - Combo Chart: 1 (dual-axis analysis)
- Geographic Visualizations:
  - Filled Maps: 2 (regional distribution)
  - Shape Map: 1 (custom regions)
- Tables: 2 (detailed data display)
- Page Navigator: 5 (multi-page navigation)

## User Interface Design

### Color Scheme
- Dark navy blue background for professional appearance
- Red accent color matching Formula 1 branding
- Yellow/gold for highlights and secondary elements
- Team-specific colors in constructor visualizations

### Layout Structure
- **Left Navigation Panel** (60px width):
  - Clear filters button (top)
  - Filter panel toggle
  - Page navigation controls
  - Back button (bottom)
  - Information button (bottom)
  
- **Main Content Area**:
  - Header with page title and F1 logo
  - KPI cards in prominent positions
  - Charts arranged in grid layout
  - Interactive maps as focal points

### Typography
- Headers: Bold, large format for page titles
- Labels: Clean, readable font for data labels
- Numbers: Large, bold format for KPI values

## Getting Started

### Prerequisites
- **Power BI Desktop** (latest version recommended)
- Download from: https://powerbi.microsoft.com/desktop/

### Installation

1. **Download the dashboard:**
```bash
git clone https://github.com/madiibam/formula1-powerbi.git
cd formula1-powerbi
```

2. **Open in Power BI Desktop:**
   - Launch Power BI Desktop
   - File → Open → Select `Formula1-Dashboard.pbix`

3. **Refresh data (if needed):**
   - Home tab → Refresh
   - Note: Data sources may need reconfiguration

## Screenshots

### 1. Main Dashboard - Formula 1 Overview
Global statistics with interactive world map, top drivers ranking, points dynamics over 70+ years, and top constructors breakdown.

### 2. Filters Panel
Comprehensive filtering system with year slider (1950-2024), constructor dropdown, driver selection, and race circuit filters.

### 3. Navigation Menu
Left-side panel with clear filters button, filter toggle, page navigation, back button, and information access.

### 4. Driver Performance Analytics
Top 5 drivers with portraits, seasonal points progression, winner analysis by starting position, podium statistics, and detailed driver table.

### 5. Driver Details Tooltip
Click on any driver photo to see: birth date, current team, wins, podiums, career points, fastest laps, and last win information (example: Max Verstappen profile).

### 6. Constructor Insights
212 total constructors with ranking table, podium distribution, points breakdown, seasonal performance, and win analysis by position.

### 7. Races & Circuits Overview
3,071 total circuits, 1,125 races, interactive location map, top tracks by race count, dynamics over time, and best circuits for constructors.

### 8. Drill-through Page - Year 1993
Detailed analysis: 16 total races, 77 circuits count, regional race distribution map, quarterly breakdown, and race/points comparison.

### 9. Interactive Features
Drill-through demonstration showing tooltip on 1991 data point with 16 races count and navigation arrow for detailed view.

## Technical Details

### Data Model
- **Size:** 6.5 MB data model
- **Tables:** Multiple fact and dimension tables
- **Relationships:** Star schema with proper key relationships

### Visualizations Breakdown
- Action Buttons: 50
- Card Visuals: 32
- Shapes & Images: 53
- Slicers: 20
- Charts: Line (3), Donut (3), Bar (2), Area (2), Column (2), Pie (1), Combo (1)
- Maps: Filled Map (2), Shape Map (1)
- Tables: 2
- Page Navigator: 5

### Performance Optimizations
- Optimized visual count per page
- Efficient DAX measures
- Proper data model design

## 📚 Data Sources

This dashboard analyzes Formula 1 data including:
- Race results and standings
- Driver statistics and career data
- Constructor/team performance
- Circuit information and locations
- Historical F1 records

**Dataset included:** 14 CSV files (~21 MB) in the `/data` folder
- Source: Kaggle Formula 1 World Championship (1950-2024)
- Last updated: July 2024
- See [data/README.md](./data/README.md) for detailed information

## Skills Demonstrated

- **Power BI Development** - Complex dashboard creation
- **Data Modeling** - Star schema, relationships, calculated columns
- **DAX** - Measures, calculated tables, time intelligence
- **UI/UX Design** - User-friendly navigation and visual hierarchy
- **Data Visualization** - Appropriate chart selection for insights

## Future Enhancements

- [ ] Real-time data refresh integration
- [ ] Predictive analytics for race outcomes
- [ ] Mobile-optimized layout
- [ ] Additional drill-through pages
- [ ] Performance optimization for faster load times
- [ ] Integration with official F1 API

## File Information

- **Filename:** `Formula1-Dashboard.pbix`
- **Size:** ~9.4 MB
- **Power BI Version:** Compatible with Power BI Desktop (2024+)
- **Last Updated:** December 2024

## Usage Tips

1. **Navigation:** Use the page navigator or action buttons to move between sections
2. **Filtering:** Apply slicers to filter data by season, driver, team, or circuit
3. **Drill-through:** Right-click on data points to access detailed analysis
4. **Export:** Use Power BI's export features to share insights

## Contributing

This is a personal portfolio project. Suggestions and feedback are welcome!

## Contact

- **Madiyar Mukaram**
- GitHub: [madiibam](https://github.com/madiibam)
- Email: madiyarmukaram@gmail.com

---

*Built with Power BI Desktop | Data Analytics Portfolio Project*
