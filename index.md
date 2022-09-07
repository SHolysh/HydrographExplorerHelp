---
title: Hydrograph Explorer Help
description: Help and quick reference for the ORMGP Hydrograph Explorer
author: Oak Ridges Moraine Groundwater Program
date: 2022-06-16
output: html_document
---

* TOC
{:toc}

# ORMGP Hydrograph Explorer - Getting Started

This document provides guidance to get started with the ORMGP's Hydrograph Explorer Tool. 

# Opening the Hydrology Explorer

The [ORMGP Hydrograph Explorer](http://shiny.oakridgeswater.ca:3838/sHydrologyMap/){:target="_blank"} is a set of graphing and interpretation tools that allow users to examine hydrologic and hydrogeologic data within the Oak Ridges Moraine (ORM) study area. The tools can be used to view X-Y plots (i.e. hydrographs) of water-level data, as well as a comprehensive suite of other statistical analyses/graphs for groundwater and surface-water locations.  Data sources include the ORMGP database as well as various online sources. 

Upon opening the [Hydrograph Explorer](http://shiny.oakridgeswater.ca:3838/sHydrologyMap/){:target="_blank"}, the user will see a basemap with an options menu on the right-hand side, as shown in _Figure 1_, below. Notice that the browser window is called _sHydrology_.

![*Figure 1: ORMGP Hydrograph Explorer*](https://raw.githubusercontent.com/OWRC/HydrographExplorerHelp/main/images/HydrogExp01.PNG)  
_Figure 1: ORMGP Hydrograph Explorer_

# Filtering Dates

To filter the available stations, users can adjust the date envelope in the upper-right, within the in the menu box. The minimum and maximum data are selected with the slider bar.  Once the min and max dates are selected, the map will refresh with only those locations that include data from within the date envelope. There's also an option to select the minimum period of data.  As an example, selecting 10 years from the dropdown menu will show locations that have at least 10 years of data. These two features are shown in Figure 2 below:

![*Figure 2: ORMGP Hydrograph Explorer - Selecting Dates*](https://raw.githubusercontent.com/OWRC/HydrographExplorerHelp/main/images/HydrogExp04.PNG)  
_Figure 2: ORMGP Hydrograph Explorer - Selecting Dates_  

# Selecting Location Type

The menu on the right side also shows the types of locations that are available. Four data options are available:
- Streamflow stations
- Climate stations 
- Deep (screen top >20 m) groundwater monitoring locations 
- Shallow groundwater monitoring locations

By default, when the map opens, locations with deep (>20 m below ground surface) groundwater monitoring data for the period 1992 - 2022 are shown. The four data types listed above can be shown alone or combined.

On the map, the user can zoom in to focus on a specific area using the roller on the mouse, or by clicking the + icon in the upper left corner of the map. Location names are shown when the mouse hovers over a specific location. 

# Opening the Hydrographs

Clicking on a location will provide the full location name, plus an option to _analyze monitoring data_, as shown in Figure 3.  Once a location is selected, a preview of the hydrograph for the selected location will appear at the bottom of the menu box on the right.
![*Figure 3: ORMGP Hydrograph Explorer - Selection of a Location*](https://raw.githubusercontent.com/OWRC/HydrographExplorerHelp/main/images/HydrogExp02.PNG)  
_Figure 3: ORMGP Hydrograph Explorer - Selection of a location_

Once a location is selected and the user clicks _analyze monitoring data_, a new web-browser tab will open with graphs and details of the selected location as shown in Figure 4. 
![*Figure 4: ORMGP Hydrograph Tools*](https://raw.githubusercontent.com/OWRC/HydrographExplorerHelp/main/images/Hydrograph01.png)  
_Figure 4: ORMGP Hydrograph Tools_

In the sHydrograph browser window, one or more X-Y graphs will shown, depending on what data is available for the selected location. For this example (Nobleton PW 3), three graphs are shown: 
1. Precipitation (including rainfall and snowmelt)
2. Production (in this case, PW 3 represents a pumping well)
3. Water levels (both static (point data) and logger (line data) are shown)
The data shown in these graphs can be toggled off or on using the check boxes on the left menu. 

For these hydrographs, precipitation ([rainfall](https://owrc.github.io/interpolants/sources/sources.html#web-data-scrapers){:target="_blank"} and [snowmelt](https://owrc.github.io/interpolants/modelling/snowmeltCCF.html){:target="_blank"}) and [air pressure](https://owrc.github.io/interpolants/interpolation/barometry.html){:target="_blank"} data are interpoolated from nearby meteorlogical stations. The remaining data (pumping rates/production and water levels) are from the ORMGP database.

The remaining statistical and graphical analyses for each location are accessed under the drop down lists near the top of the browser window. above the graphs. 


