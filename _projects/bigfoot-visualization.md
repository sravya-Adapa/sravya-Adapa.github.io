---
name: Bigfoot Sightings Visualization
tools: [Python, Altair, Vega-Lite]
image: assets/pngs/bigfoot_thumb.png
description: Interactive visualizations of Bigfoot sighting reports across the U.S. using Altair & Vega-Lite.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Bigfoot Sightings Visualization

This project visualizes Bigfoot sighting reports across the United States between 1950 and 2020.  
Data source: [BFRO Reports Dataset](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv)

<div style="text-align:center;">
  <vegachart schema-url="{{ site.baseurl }}/chart1.json" style="max-width: 90%; margin:auto; display:block;"></vegachart>
</div>

---

## Interactive Map by Year

This map shows where and when Bigfoot sightings were reported between 1950 and 2020.  
Use the slider to filter sightings by year.

<vegachart schema-url="{{ site.baseurl }}/chart2.json" style="width: 100%"></vegachart>

---

## Search The Data & Methods

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/sravya-Adapa/sravya-Adapa.github.io/blob/main/bigfoot_visualizations.ipynb" text="The Analysis" %}
</div>
