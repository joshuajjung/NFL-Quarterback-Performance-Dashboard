# NFL-Quarterback-Performance-Dashboard

**Live Dashboard → [View on Tableau Public] (https://public.tableau.com/shared/GJZJP2GRG?:display_count=n&:origin=viz_share_link)

---

### Goal
Analyze NFL quarterback performance using passing yards, weekly trends, and projections.

### Data
Data is from [hvpkod's NFL-Data repo](https://github.com/hvpkod/NFL-Data).

### Process
- Imported data from multiple separate CSV files: QB Season stats, QB Weekly stats (one file per week), and QB Weekly Projections(one file per week).
- Used a wildcard union in Tableau to combine weekly files efficiently.
- Blended data sources by Player Name to link actual performance with projections.
- Built interactivity using filters + dashboard actions to sync views across multiple data sources.

### Dashboard Features
- Top QB passing yards (bar chart)  
- Weekly yard trends (line chart)  
- Projected vs. actual performance (line chart)  
- Filters: select a QB via bar chart or dropdown search  

### Key Insights
- Joe Burrow, Jared Goff, and Lamar Jackson consistently outperformed projections in the 2024 season.
