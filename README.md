# nasa-water-storage-analysis
california central valley and inner niger delta using GRACE data
#It compares the water futures in the two different regions ie at the California central valley and the other is in Inner Niger Delta.
## DATA SOURCE
NASA GRACE/GRACE-FO combined with GLDAS 2.1
 Accessed through GEOGloWS GRACE Regional Analyst
  (https://apps.geoglows.org/grace-anomalies)
 Variables: TWSa (total water storage anomaly), GWSa (groundwater storage anomaly)
 Gap filling: straight line
 Period: 2002 to [end year]
 Downloaded on: 15 Nov 2026

## Files
central_valley.csv: monthly time series for the Central Valley
inner_niger_delta.csv: monthly time series for the Inner Niger Delta
  
## Method
1. Selected each region in GRACE Regional Analyst.
2. Chose the GRACE + GLDAS 2.1 dataset.
3. Exported the TWSa and GWSa time series as CSV.
4. Uploaded the files to this repository.

## Results
Central Valley: [trend in cm/yr]
Inner Niger Delta: [trend in cm/yr]
Comparison: The California Central Valley loses groundwater at a rate more than 20 times faster than the Taoudeni-Tanezrouft Basin due to heavy agricultual pumpimg and recurring severe droughts.
The vertical axis for the Central Valley spans 100 cm (-60 to +40 cm), whereas the Taoudeni-Tanezrouft Basin spans just 8 cm (-4 to +4 cm), highlighting how extreme the wet-and-dry swings are in California compared to the arid Saharan aquifer.
TWSA vs. GWSA Alignment: In the Central Valley, the total water storage trend (-1.30 cm/yr) closely mirrors the groundwater trend (-1.35 cm/yr), showing that groundwater loss drives overall water depletion. In the Taoudeni-Tanezrouft Basin, total water storage slightly increases (+0.02 cm/yr) even as groundwater shows a tiny decline (-0.06 cm/yr).

## Limitations
GRACE resolution is roughly 300 km, so results for the small
Inner Niger Delta are approximate.

## Credits
NASA GRACE/GRACE-FO, GLDAS, GEOGloWS.
