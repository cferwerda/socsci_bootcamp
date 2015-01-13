Jump to...
  * [Data](#datahead)
  * [Tools - TimeMapper](#timemaphead)
  * [Tools - ArcGIS Online](#agxohead)
  * [Tools - CartoDB](#cartodbhead)

---
## <a name="datahead"></a>DATA
The data are stored on Google Drive. The link will be shared with you during the workshop.
####Civil War Battles
* civil_war_battles.zip – point shapefile (zipped) of locations of battles, 1861-1865
* civil_war_states.zip – polygon shapefile (zipped) of state outlines as of 18___, categorized by allegiance
* Civil War Battles spreadsheet – all battles in spreadsheet format, for use in TimeMapper
* Civil War Battles TimeMapper Example Spreadsheet – an example of how to format a spreadsheet to use in TimeMapper
* Civil War Battles Variable Descriptions.pdf – metadata for the Civil War datasets

####Adult Obesity in the US
* state_obesity.zip – polygon shapefile (zipped) of state outlines with obesity data
* ma_obesity.zip – polygon shapefile (zipped) of Massachusetts counties with obesity and demographic data
* Obesity Variable Descriptions spreadsheet – metadata for obesity variables
* Find other layers at [MassGIS](http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/datalayers/) 

####Tornadoes, 1950-present
* tornadoes3.zip – point shapefile (zipped) of locations of all tornadoes of at least a magnitude of 3 on the EF-scale, 1950-2013
* tornado.zip at <http://www.spc.noaa.gov/gis/svrgis/> – line shapefile of tracks of all tornadoes (magnitudes 1-5), 1950-2013
* Tornado Variable Descriptions.pdf – metadata for the tornado datasets
* CountyPop2010.zip – polygon shapefile (zipped) of county outlines with population information

## TOOLS
###<a name="timemaphead"></a>TimeMapper  <http://timemapper.okfnlabs.org/>
To use TimeMapper, you need a Google account so that you can create a Google spreadsheet. Creating a TimeMapper account is optional, but it allows you to edit your maps later on.
####To learn how to use it:
*First*, watch the 1 minute tutorial on the website.

*Then* look at the example Civil War [spreadsheet](https://docs.google.com/spreadsheets/d/1E_r2WyxQmk7SNQhjeWBWz_R6Pv-DMe8kZjHb3TOM9GA/edit?usp=sharing) and [map](http://timemapper.okfnlabs.org/carolinferwerda/civil-war-battles-timemapper-example-spreadsheet).

*General steps:*
1. Decide what you want to focus on. (All battles in a particular year? Only decisive battles? Battles in a particular area or involving particular commanders?)
2. Create a new spreadsheet with the battles of interest. Format the spreadsheet so that TimeMapper can read it.
3. Find any additional media for each battles (an image or youtube video) and paste the link in the Media column of the spreadsheet. Fill in source information, descriptions, etc. This is the part where you can customize the message of the map!
4. Publish the map according to the instructions on the TimeMapper website. Share the link to your map with others!

---
###<a name="agxohead"></a>ArcGIS Online  <https://www.arcgis.com/home/signin.html>
You will be provided with temporary accounts during the workshop. The accounts will remain available to you until 1/21, after which all content will be deleted as these accounts will be used in other trainings.

Go to [**http://esrit3g.maps.arcgis.com**](http://esrit3g.maps.arcgis.com) to log in for this workshop.
####Get Started
Sign in and click MAP at the top of the page to open the map viewer.

Take the guided tour for a quick overview.
####Add Data
#####Search for Layers
A few datasets have already been uploaded for you. You can also use this feature to find datasets posted across ArcGIS Online. You can search within your organization, across the web, or in particular groups.

For today, look in the NEASSIST 2015 Workshop Group.
#####Upload Data
#####Search for Data on ArcGIS Online
####Make a Map

####Share Your Map

---
###<a name="cartodbhead"></a>CartoDB  <http://cartodb.com/>
Go to the website to sign up for a free account. Chrome is the recommended browser for this tool.
####Add Data
**File formats:** CSV, Excel, ESRI Shapefiles, and GPX files

1. Go to your CartoDB dashboard (https://yourusername.cartodb.com/dashboard/)  and click *New Table* (the big plus sign in the right side of the screen).
2. Now you have several ways to bring in datasets. Two commonly options:
  * *Upload Data:* Shapefiles must be compressed in a zip archive (\*.zip) before uploading. Choose *select a file* or drag and drop the zip file onto the New table window.
  * *Import from URL:* Paste a URL to a data file into the field. The URL should be to a supported file type. For example, if we want to import a layer showing libraries in MA from the MassGIS website, the .html URL for the [datalayer’s info page](http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/datalayers/libraries.html) won’t work; instead, we want the direct link to the libraries.zip file, which is the [*Download this layer: ESRI Shapefile* link](http://wsgw.mass.gov/data/gispub/shape/state/libraries.zip). ![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/massgis_libraries.jpg "MassGIS Data Site")
  * Additional help: http://docs.cartodb.com/tutorials/import_shapefile_in_cartodb.html

####Make a Map
#####View Your Data
  ![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_datamapview.jpg "2 views to work with data in CartoDB")

* **Data View**: Once you add data, you will first see it as a table in Data View. This shows you the variables for each feature (row) in the dataset as a spreadsheet. You can use this table view to format, query, and edit the data.

* **Map View**: This shows you the data located on a map – you may need to zoom or pan to it.

#####Style Your Data
The map view allows you to change how the data look on a map; however, if you want to share your map with others, then you should create a visualization – click *Visualize* in the top-right corner of the screen. 

Next, use the [tools in the sidebar](http://docs.cartodb.com/cartodb-editor.html#cartodb-sidebar) on the right side of the screen in Map View to change the appearance of the data in the map. 

![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_wizard.jpg "the style wizard") Start with the [Wizards tool] (http://docs.cartodb.com/cartodb-editor.html#wizards) to change the colors and size, or to make a chloropleth map. Within each way to style the data, you can change the appearance of it in the map. Try out the settings to see how they work, or check out [the help] (http://docs.cartodb.com/cartodb-editor.html#wizards) for details.

![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_infowindow.jpg "the info window tool") Next, change what shows up in the [info windows] (http://docs.cartodb.com/cartodb-editor.html#info-windows) by clicking on the tool and adjusting which fields are visible.
#####Add Map Elements
Click the *Add Element* button on the lefthand side of the screen. This allows you to add a legend, text box, annotation (linked to a particular location & zoom level), or image (e.g., a logo). Simply drag and drop to move them to the desired location, and click on an element to activate the formatting toolbar. Click [here] (http://docs.cartodb.com/cartodb-editor.html#add-element) for more details.

![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_legend.jpg "the legend tool") To add a legend, use the [Legends tool] (http://docs.cartodb.com/cartodb-editor.html#legends) in the right-hand side bar. This is particularly useful if the colors on the map are meaningful (i.e., more than simple symbology).
#####Add Another Layer to the Map
Click the blue plus sign at the top of the right-hand toolbar to *Add layers* and then find the layer you want. You can select an existing layer or upload a new one.

You can toggle between the layers in the right-hand toolbar to change how each is styled. [More details](http://docs.cartodb.com/tutorials/multilayer_overview.html)
#####Animate the Map to Show Change over Time
Note that this only works for point data (not polygons or lines). The tool called [Torque](http://docs.cartodb.com/tutorials/introduction_torque.html) allows you to animate your data based on a numeric value.

In the Wizard tool, find Torque. It will be automatically enabled in the Visualization wizard if you are working with a point layer.
####Share Your Map
Use the *Share* button in the top-right corner to share your map.

####Learn more about CartoDB
* [Use SQL to interact with, query, and edit your data.](http://docs.cartodb.com/tips-and-tricks.html#the-power-of-cartodb)
* [Tutorials](http://academy.cartodb.com/)
* [CartoDB Map of the Week](http://blog.cartodb.com/categories/map-of-the-week/)

---
## Data Sources
* **State and county outlines:** Global Administrative Areas database, <gadm.org>
* **US adult obesity by state:**  Centers for Disease Control and Prevention (CDC). Behavioral Risk Factor Surveillance System Survey Data. Atlanta, Georgia: U.S. Department of Health and Human Services, Centers for Disease Control and Prevention. <http://apps.nccd.cdc.gov/brfss/>
* **MA adult obesity:**  CDC, Diabetes Interactive Atlas, County Indicators, <http://www.cdc.gov/diabetes/atlas/countydata/County_ListofIndicators.html>
* **Population and census data:** US Census Bureau, American FactFinder, <https://factfinder2.census.gov/>
* **Civil War battle locations:** Robert Stewart, Jeremy Newcomb, and Chris Bunin. 2007. The Virginia Experiment. Data are restricted for educational purposes only. Downloaded from [ArcGIS Online](http://www.arcgis.com/home/item.html?id=e47e30d956d146498624f18b423a8f97). 
