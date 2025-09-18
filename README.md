# Amazon-prime-Movies-TV-Shows-Power-BI-Dashboard-
🎬 Amazon Prime Movies & TV Shows – Power BI Dashboard (Detailed Plan)

1️⃣ KPI Cards (Top Row)

Show at a glance the key metrics:

Total Titles → COUNTROWS(Table)

Total Movies → CALCULATE(COUNTROWS(Table), Table[type] = "Movie")

Total TV Shows → CALCULATE(COUNTROWS(Table), Table[type] = "TV Show")

Average Rating → AVERAGE(Table[rating])

Earliest Release Year → MIN(Table[release_year])

Latest Release Year → MAX(Table[release_year])



---

2️⃣ Movies vs. TV Shows Split

Visual: Donut/Pie Chart

Data: Count of Titles by Type




---

3️⃣ Content by Year (Trends)

Visual: Line Chart

X-axis: Release Year

Y-axis: Count of Titles

Legend: Type (Movie / TV Show)





---

4️⃣ Country-wise Availability

Visual: Map (Filled Map) or Bar Chart

Data: Count of Titles by Country







---

5️⃣ Genres / Categories

Visual: Treemap or Bar Chart

Data: Count of Titles by Genre





---

6️⃣ Actors & Directors Analysis

Visual 1: Bar Chart (Top 10 Actors by Title Count)

Visual 2: Bar Chart (Top 10 Directors by Title Count)




---

7️⃣ Ratings Analysis

Visual 1: Histogram → Distribution of Ratings

Visual 2: Scatter Plot → Ratings vs Release Year





---

🎨 Suggested Layout (2 Pages in Power BI)

Page 1: Overview Dashboard

Top → KPI Cards

Middle Left → Donut (Movies vs TV Shows)

Middle Right → Bar Chart (Top Countries)

Bottom → Line Chart (Trend by Year)


Page 2: Deeper Insights

Left → Treemap (Genres)

Right Top → Bar Chart (Top Actors)

Right Bottom → Bar Chart (Top Directors)

Bottom → Histogram (Ratings)



---

🎯 Extra Features to Add (Optional)

Slicers/Filters: Year, Country, Type (Movie/TV Show), Genre

Drill-through Page: For a specific Actor/Director to see all their work

Theme: Use Amazon Prime colors →

Dark Blue #0F171E

Light Blue #00A8E1
