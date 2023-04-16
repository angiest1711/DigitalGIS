# Glacier Monitoring of the Sierra Nevada del Cocuy, Colombia using Landsat Satellite Imagery 

Colombia despite of being a tropical country has glaciers that can be found at the top of the mountains that are higher than 4800 meters above sea level. In the past the country had fourteen glaciers but due to the increasing temperatures only six remain, one of them is the Sierra Nevada del Cocuy (IDEAM, 2021).

## Study Area
The Sierra Nevada del Cocuy is located in the eastern Andes Mountain chain between the Arauca, Boyacá and Casanare. It is the largest glacier in the country and is part of the Natural National Park El Cocuy. (Parques Nacionales, n.d)

## Methodology

Landsat 8 and 9 Level – 2 scenes were used the study case mainly from the month of December (2022,2021,2020,2017,2016,2014), but due to cloud coverage, some scenes belong to a different time frame (2023,2018). The scenes were obtained through the Earth Explorer website.
The Normalized Difference Snow Index was used, making possible to differentiate snow from other variables such as vegetation or soil (USGS, n.d).

(G – SWIR1) / (G + SWIR1)

According to the USGS, in Landsat 8-9, NDSI = (Band 3 – Band 6) / (Band 3 + Band 6).

After getting each scene NDSI, the Semi Automated Classification plugin was used and train to obtain the snow polygon. The different polygons allow to calculate the estimate area. 

Results

The different areas obtained by the semi automated classification show a reduction through the years, in which the snowed area is beginning to be divided in different sections.
https://user-images.githubusercontent.com/119541571/232234640-ae179fcb-e61f-41fd-b925-6c45e1878188.mp4
When calculating the areas, is possible to apreciate a recovery in the 2020-2022 period, despite of this, it continues the retreat tendency of the glacier area
![Table_cocuy](https://user-images.githubusercontent.com/119541571/232345451-9fab28c5-238e-4262-8010-53b07a27b26a.jpg)
![area_cocuy](https://user-images.githubusercontent.com/119541571/232345732-c906166b-3990-4f1b-a716-9e25151d94c9.jpg)

IDEAM, 2021, SIERRA NEVADA EL COCUY O GÜICÁN
USGS, (n.d), Normalized Difference Snow Index



