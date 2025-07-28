# SCT_TASK_4
#  Traffic Accident Data Analysis

This project is part of my internship at **[SKILLCRAFT TECHNOLOGY]**, focusing on real-world data analytics.  
The task involved analyzing a large traffic accident dataset (~2.5 GB) using Python and extracting meaningful insights about when, where, and why road accidents occur.

---

##  Project Structure

- **SCT(TASK(4)).ipynb** – Main Jupyter Notebook with code, analysis, and visualizations
- **Dataset** – A large CSV file (not uploaded due to size)
- **Video Demo** – [SCT(TASK(4)).mp4]

---

##  Objective

To identify patterns in traffic accidents based on:
- Time of day (hour, day of week, month)
- Weather conditions
- Road environment factors (e.g. junctions, traffic signals, crossings)
- Accident hotspots (top cities)

---

##  Tools & Libraries

- Python 3
- Pandas
- Dask (for large CSV loading)
- Seaborn & Matplotlib
- Jupyter Notebook

---

##  Key Analysis Performed

1. **Data Cleaning & Preprocessing**
   - Converted date columns
   - Removed missing/null values
   - Created new time-based features

2. **Exploratory Data Analysis (EDA)**
   - Accidents by hour, day of week, and month
   - Accidents by weather and visibility
   - Accidents involving traffic signals, crossings, bumps, etc.
   - City-wise accident count (to detect hotspots)

3. **Visualizations**
   - Count plots, bar charts, and time-based charts
   - Feature-wise comparison of conditions during accidents

---

##  Insights Gained

- Peak accident hours are usually between 6–9 AM and 3–6 PM
- Weather conditions like fog, rain, and snow correlate with higher accident counts
- Cities with dense urban layouts have more reported incidents
- Road features like junctions and crossings show higher accident density

---

##  Demo Video (Optional)

If you want to watch the live notebook execution:
>  [Watch Task 4 Demo (MP4)]

---

##  Learnings

- Efficiently handling large datasets with Dask
- Feature engineering with time and boolean road conditions
- Data storytelling through clean, effective plots
- Real-world data interpretation for safety-related decisions

---

