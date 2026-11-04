# Day 2 — Lines

!["GLOWING MAP"](02.Lines_Bucharest_Tram_System.png)

Bucharest's tram network, lit up like a neuron.

## Data

- **Tram lines:** OpenStreetMap, downloaded with the QuickOSM plugin in QGIS (`railway = tram`, Bucharest area)
- Only the line features were used; the points layer was hidden

## Method

1. Queried OpenStreetMap for every tram line in Bucharest using QuickOSM
2. Saved the result as a GeoPackage, so a crash couldn't wipe it out (learned the hard way)
3. Styled the lines with QGIS's built-in neon effect, then softened the glow (smaller spread and blur, glow colour matched to the line)
4. Set a near-black navy background 
5. Exported at 300 dpi

A super fun early morning project, keeping things simple (or trying to). 
Learned the hard way to save your project early and frequently. Patience goes a long way, so go make that coffee. Also experimented with different backgrounds and symbology properties, including hillshade which...well, Bucharest is practically flat. I also got some troubleshooting practice: a hidden error on the Project Properties Elevation page was blocking the whole window from saving, including the lovely deep blue background I wanted. A quick change, setting the terrain to "Flat",  fixed it. 


## Credits

Data: © OpenStreetMap contributors (ODbL) · Tools: QGIS, QuickOSM · #30DayMapChallenge
