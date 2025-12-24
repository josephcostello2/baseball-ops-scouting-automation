# MLB Pitcher Scouting & Automation Pipeline

### **Overview**
This project automates the collection and analysis of Statcast data to support Baseball Operations and Coaching staff. It demonstrates an end-to-end workflow: fetching raw data, managing it via SQL, and generating actionable visualizations for game planning.

---

### **Key Features**
* **Automated Data Ingestion:** Uses `pybaseball` to fetch real-time Statcast data.
* **SQL Integration:** Simulates a professional Baseball Ops environment by warehousing data in a local SQLite database for efficient querying.
* **Performance Metrics:** Calculates advanced metrics such as **Whiff%** per pitch type and velocity differentials.
* **Strategic Visualization:** Includes Pitch Movement profiles and Strike Zone heatmaps to identify pitcher trends and "tunneling" opportunities.

![Tyler Glasnow Pitch Movement Profile](movement_plot.png)

---

### **How to Use**
1.  **Open in Colab:** Click the "Open in Colab" button inside the `.ipynb` file to run the analysis.
2.  **SQL Queries:** The notebook includes SQL blocks to demonstrate how to pull specific pitcher trends from the database.
3.  **Requirements:** All dependencies are listed in `requirements.txt`.

---

### **Business Impact (Baseball Ops Context)**
This tool reduces the manual workload for analysts by automating the "Pre-Game" data pull. It allows coaches to quickly see which pitches have the highest swing-and-miss probability and where a pitcher is most likely to locate them in critical counts.
