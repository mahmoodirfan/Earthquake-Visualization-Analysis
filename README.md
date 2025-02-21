Earthquake Visualization and Analysis 🌍🌋

Overview
This Python project fetches the latest earthquake data from the USGS Earthquake API, visualizes the data on an interactive map using Folium, and performs statistical analysis using Pandas, GeoPandas, and Seaborn. The project also generates insightful plots for earthquake magnitude distribution and depth-magnitude relationships.

Features
✅ Fetches real-time earthquake data (last 30 days) from USGS
✅ Creates an interactive map with earthquake locations and magnitudes
✅ Generates a heatmap of earthquake activity
✅ Performs statistical analysis on magnitude, depth, and locations
✅ Saves output files:

📍 Interactive Map (earthquake_map.html)
📊 Magnitude Distribution & Depth Analysis (earthquake_analysis.png)
📜 Summary of Key Findings (earthquake_analysis.txt)

**Technologies Used**
Python
GeoPandas (for spatial data handling)
Folium (for interactive mapping)
Matplotlib & Seaborn (for visualization)
Requests (for API data fetching)
Shapely (for geometry processing)
How to Run
Clone this repository:
bash
Copy
Edit
git clone https://github.com/yourusername/Earthquake-Visualization-Analysis.git
cd Earthquake-Visualization-Analysis
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the script:
bash
Copy
Edit
python earthquake_analysis.py

**Expected Outputs**
A dynamic earthquake map with magnitude markers
A heatmap for intensity visualization
Graphs showing earthquake magnitude distribution and depth correlation
A text-based summary analysis
📌 Use Case: This tool is useful for researchers, geologists, and anyone interested in monitoring global earthquake activity in a visually informative way.

🚀 Contributions are welcome! Feel free to improve the script or add new functionalities.
