---
layout: project
title: "Bigfoot Sightings Visualization"
subtitle: "Interactive Altair Visualizations of Bigfoot Reports in the U.S."
date: 2025-11-12
tags: [Python, Altair, Vega-Lite, Data Visualization]
thumbnail: ../chart1.html
links:
  - label: "View Dataset"
    url: "https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv"
  - label: "View Notebook"
    url: "https://github.com/sravya-Adapa/sravya-Adapa.github.io/blob/main/bigfoot_visualizations.ipynb"
---

##  Visualization 1: Sightings by State
This bar chart visualizes the number of Bigfoot sightings across U.S. states. The x-axis represents states, and the y-axis shows how many sightings were reported in each.  
I used a **bar mark** with a **color encoding** (`reds` color scheme) to emphasize states with more sightings.

<iframe src="../chart1.html" width="850" height="500"></iframe>

---

##  Visualization 2: Interactive Map by Year
This interactive map shows where Bigfoot sightings occurred between 1950 and 2020.  
Each circle represents a sighting by **latitude** and **longitude**, and color encodes the **year**.  
The map uses an **Albers USA projection**, and includes a **year slider** that allows viewers to explore sightings over time.

<iframe src="../chart2.html" width="850" height="500"></iframe>

---

###  Interactivity Discussion
The slider allows users to explore temporal patterns of sightings. This interaction makes the visualization more engaging and highlights trends that are not visible in static charts.
