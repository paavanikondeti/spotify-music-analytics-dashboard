# 🎵 Spotify Music Analytics Dashboard

## 📌 Project Overview
This project is an interactive Excel-based Spotify Analytics Dashboard created using a real-world Spotify tracks dataset. The project focuses on transforming raw music streaming data into meaningful insights through data cleaning, analysis, visualization, and dashboard design.

The dashboard was built to simulate a real data analyst workflow using Microsoft Excel tools such as Pivot Tables, Charts, KPI Cards, Conditional Formatting, Slicers, and Data Transformation techniques.

# 🎯 Project Objectives
* Analyze Spotify track data
* Identify top-performing artists
* Understand popularity trends
* Explore track characteristics such as energy and danceability
* Build an interactive dashboard for data-driven insights

# 🛠️ Tools & Features Used
* Microsoft Excel
* Excel Tables
* Pivot Tables
* Pivot Charts
* Slicers
* KPI Cards
* Conditional Formatting
* Data Cleaning
* Dashboard Design
* IF Functions
* COUNTA / AVERAGE / UNIQUE formulas

# 📂 Workbook Structure
## 1️⃣ Raw_Data Sheet
This sheet contains the original Spotify dataset imported from a CSV file.

### Tasks Performed
* Imported raw Spotify tracks dataset
* Converted raw data into an Excel Table
* Renamed table for structured analysis
* Preserved original dataset for reference and backup

### Dataset Included
* Track information
* Artist names
* Album names
* Popularity scores
* Audio features
* Genre information
* Explicit content indicators
* Duration metrics

## 2️⃣ Cleaned_Data Sheet
This sheet contains the cleaned and transformed version of the dataset prepared for analysis.

### Data Cleaning Steps
* Removed duplicate records using `track_id`
* Checked missing/null values
* Standardized data structure
* Converted `duration_ms` into minutes
* Created new calculated columns

### Feature Engineering
Additional analytical columns were created:

| New Column         | Purpose                                                   |
| ------------------ | --------------------------------------------------------- |
| `duration_min`     | Song duration in minutes                                  |
| `popularity_level` | Categorized songs as Hit, Popular, Average, or Low        |
| `content_type`     | Converted TRUE/FALSE explicit values into readable labels |
| `energy_level`     | Categorized songs by energy score                         |
| `dance_type`       | Categorized songs by danceability                         |

### Functions Used
* `IF`
* Nested `IF`
* `ROUND`
* Table Structured References

## 3️⃣ Pivot_Analysis Sheet
This sheet contains Pivot Tables and Pivot Charts used for exploratory data analysis.

### Analysis Performed
* Top Artists by Average Popularity
* Explicit vs Clean Track Distribution
* KPI calculations
* Aggregated popularity analysis

### Pivot Features Used
* Average aggregation
* Count aggregation
* Sorting
* Value filters
* Pivot Charts

### Visualizations Created
* Horizontal Bar Chart
* Doughnut Chart

## 4️⃣ Dashboard Sheet
This sheet contains the final interactive Spotify Analytics Dashboard.

### Dashboard Features
* Spotify-inspired dark theme
* KPI Cards
* Interactive slicers
* Pivot Charts
* Insights section
* Dynamic filtering

### KPIs Included
* Total Tracks
* Average Popularity
* Average Duration
* Unique Artists

### Interactive Elements
Slicers were added for:
* Content Type
* Popularity Level
* Energy Level

### Insights Generated
Examples:
* High-energy tracks tend to have higher popularity
* Top artists maintain consistently strong popularity scores
* Clean tracks dominate the selected sample dataset

# 📊 Key Skills Demonstrated
* Data Cleaning
* Data Transformation
* Exploratory Data Analysis (EDA)
* Dashboard Design
* Data Visualization
* Business Insight Generation
* Excel Reporting
* Interactive Reporting

# 🚀 Learning Outcomes
Through this project, the following Excel and analytical skills were strengthened:
* Working with real-world datasets
* Building Pivot Table reports
* Creating interactive dashboards
* Designing KPI cards
* Using slicers for dynamic filtering
* Applying analytical thinking to data problems

# 📸 Dashboard Preview
<img width="1920" height="1020" alt="Dashboard" src="https://github.com/user-attachments/assets/ee9bea7c-e4d9-4d76-bc01-8a3ac73103e7" />

# 📁 Dataset Source
Spotify Tracks Dataset from Kaggle

# 🔥 Future Improvements
Potential future enhancements include:
* Power Query automation
* Advanced dashboard interactions
* Additional analytical KPIs
* Power BI version of the dashboard
* SQL integration for larger datasets

# 👩‍💻 Author
Paavani Kondeti
