## Nuclear Power Plant Risk Assessment — Interactive MAP

## About
In August 2025, Taiwan held its third referendum in its history on the fate of nuclear power plants. However, restarting the Third Nuclear Power Plant carries numerous risks, including geological and seismic threats, aging equipment failure (such as pressure vessel embrittlement), enormous decommissioning and maintenance costs, overflowing used fuel pools, and difficulties in nuclear disaster evacuation.

This map uses spatial data analysis to represent the villages and estimated population within the 8-kilometer emergency response zone of the nuclear power plant.

## Data Sources
- Village boundary shapefile: National Land Surveying and Mapping Center, Taiwan (2025)
- Plant coordinates: Atomic Energy Council, Taiwan

## Methods
- Python (geopandas, folium, shapely)
- Coordinate system: TWD97 (EPSG:3826) converted to WGS84 (EPSG:4326)
- Spatial intersection of 8km buffer zone with village boundaries

## Key Findings
15 villages fall within the 8km emergency zone, with an estimated 
population of 24,737 residents:
- Hengchun Township: 14 villages
- Manzhou Township: 1 village
