# WorldWideEarthquake
Plots earthquakes using MATLAB Editor
- This is a fun project and intended to test out the capibilities of MATLAB editor. 
- For more information, you can access (https://jhchong.weebly.com/blog/introducing-worldwideearthquake)

Contact: Jeng Hann, Chong (jenghann.chong.43@my.csun.edu). 
  

## Requirements for all versions
- Downloaded MATLAB 
- Internet access to USGS
- Download ```borders```, ```etopo1_ice_gi2```, ```m_map```
  - ```borders``` and ```m_map``` is provided in WWE_v2
  - You need to download ```etopo1_ice_gi2``` as per instructions from m_map    (https://www.ngdc.noaa.gov/mgg/global/relief/ETOPO1/data/ice_surface/grid_registered/binary/etopo1_ice_g_i2.zip)
  - You will need to have these folders in the same directory as the WorldWideEQ scripts

## Notes
**Version 1.0**
- Allows the selection to plot in selected region
- You need to have your own shapefiles for faults 

![Version 1.0 default interface](https://github.com/jhchong11/WorldWideEarthquake/blob/master/Images/example2.png)

**Version 2.0**
- Focuses on region based on largest magnitude or recent most earthquake (free to choose)
  - You will need to modify the script for fixed locations or use Version 1.0
- Internet accessed fault maps from Global Earthquake Model (GEM) or pre-downloaded of your own shapefile

![Version 2.0 default interface](https://github.com/jhchong11/WorldWideEarthquake/blob/master/Images/example1.png)

## History and Updates
**Version 2.1**  _publishing late Summer 2020_
  - [new] Auto-refresh enabled
  - Allowed to refresh at your own rate or to not refresh
  - Improved appearance 
  
**Version 1.1** _publishing late Summer 2020_
  - Includes auto-refresh
  - Allowed to refresh at your own rate or to not refresh


_Do send me an email if you encounter any problems, questions or suggestions. This was created in **R2017b** version of MATLAB._
