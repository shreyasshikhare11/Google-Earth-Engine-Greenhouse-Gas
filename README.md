# Google-Earth-Engine-Greenhouse-Gas
Monitoring and analysing greenhouse gas (GHG) emissions and carbon sequestration. By integrating petabyte-scale satellite data with machine learning, it enables researchers and businesses to track pollutants like CO₂, methane (CH₄), and nitrogen dioxide (NO₂) globally.

This is a city-scale greenhouse gas monitoring dashboard built on Google Earth Engine, using satellite data from the European Space Agency's Sentinel-5P TROPOMI instrument — one of the most precise atmospheric sensors currently in orbit, providing daily global coverage.

We're tracking four key atmospheric pollutants simultaneously: Methane, Carbon Monoxide, Nitrogen Dioxide, and Formaldehyde. Each of these is a recognised indicator of industrial activity, traffic emissions, and broader climate impact. The analysis covers any city we define, within a 20-kilometre radius, over any time period we choose.

Before any analysis is run, we apply atmospheric quality filters to each dataset. This removes observations affected by extreme sun angles or heavy cloud cover — ensuring that what we're seeing on the map and in the charts reflects genuine ground-level atmospheric conditions, not sensor noise or weather interference.
What the Map Shows

The map displays the average concentration of each gas over the selected period, colour-coded from blue through to red — blue indicating lower concentrations and red indicating pollution hotspots. This gives an immediate, visual understanding of where emissions are elevated across the city.

The time-series charts break that data down month by month, showing how each gas concentration has changed over time. We've also built in a trend line, so you can immediately see whether pollution levels are rising, falling, or holding steady across the period.

To run this for a different city, a different gas, or a different time period, we change just a few lines. It is fully redeployable with minimal effort.
