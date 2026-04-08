# artist-audience-analysis

# Music Audience Network Analysis:

### 🎵 Project Inspiration
This project was inspired by the global success of **ROSÉ & Bruno Mars's "APT."**. Beyond its viral nature, I wanted to visualize the **cross-cultural resonance** and the invisible "bridges" that connect disparate global fanbases. This tool is designed to help marketing teams to identify "low-resistance" migration paths for artists.

### 🔗 Live Interactive Maps
* **[View Small Dataset (200 Connections)](https://mt-msc.github.io/artist-audience-analysis/)**
* **[View Scaled Dataset (2,500+ Connections)]**

### 🛠️ Technical Stack
* **Language**: Python
* **Data Source**: Last.fm API (Collaborative Filtering data)
* **Graph Theory**: NetworkX (Betweenness & Eigenvector Centrality)
* **Visualization**: Pyvis (Physics-based interactive rendering)
* **Analysis Tools**: Pandas, Requests

### 🧠 Core Methodology
1. **Automated ETL**: Built a recursive scraper to bypass streaming "black-box" limitations, extracting weighted audience overlap data.
2. **Topological Metrics**: Calculated **Betweenness Centrality** to identify "Bridge Nodes"—artists like **ROSÉ** or **Bruno Mars** who serve as hubs between sub-cultures (e.g., K-Pop and Western Pop).
3. **Business Insight**: Defined "Bridge Potential" to help optimize **Marketing ROI** and lower **Customer Acquisition Costs (CAC)** by targeting high-influence micro-communities.
