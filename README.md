Jump to...
  * [Data](#datahead)
  * [Tools - ArcGIS Online](#agxohead)
  * [Tools - CartoDB](#cartodbhead)

---
## <a name="datahead"></a>DATA
The data are stored [here](https://drive.google.com/folderview?id=0B1lTuXNNu47_flVKMXVvR2ZEMWlTLXo2VFVmaVh3Y2hkQ05oMGt2SEFVSUlIcXRlcnJoakk&usp=sharing) (or type http://bit.ly/SSB-2015 into your browser). You should be able to access the files without signing in to Google. Open a folder, click on a .zip file, and click the download button at the top of the page ![alt text](https://raw.githubusercontent.com/cferwerda/socsci_bootcamp/master/img/gdrive_download.jpg "Download button in Google Drive"). It is NOT necessary to unzip the files after downloading.
####Civil War Battles
* civil_war_battles.zip – point shapefile (zipped) of locations of battles, 1861-1865
* civil_war_states.zip – polygon shapefile (zipped) of state outlines in 1860s, categorized by allegiance
* Civil War Battles Variable Descriptions.pdf – metadata for the Civil War datasets

####Adult Obesity in the US
* state_obesity.zip – polygon shapefile (zipped) of state outlines with obesity data
* ma_obesity.zip – polygon shapefile (zipped) of Massachusetts counties with obesity and demographic data
* Obesity Variable Descriptions.pdf – metadata for obesity variables
* Find other layers at [MassGIS](http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/datalayers/) 

## TOOLS
###<a name="agxohead"></a>ArcGIS Online
You will be provided with temporary accounts during the workshop. The accounts will remain available to you until 6/9, after which all content will be deleted as these accounts will be used in other trainings.

Go to [**http://esrit3g.maps.arcgis.com**](http://esrit3g.maps.arcgis.com) to log in for this workshop.
####Get Started
Sign in and click *MAP* at the top of the page to open the map viewer.

Take the guided tour for a quick overview.
####Add Data
Click on the **Add** drop-down menu in the left panel to add data layers.
#####Search for Layers
Use this feature to find datasets posted in your organization, a group, on the web, or on ArcGIS Online. 

Start by looking within the *SocSci Bootcamp 2015 Group*.
![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/agxo_searchforshp.jpg "Search for Layers within the SocSci Bootcamp group")

Click the *Add* link next to civilwar_battles to add the layer to your map.

Try finding others layers within ArcGIS Online.
#####Add Layer from File
**File formats:** CSV, Excel, ESRI Shapefiles (zipped), GPX files, KML/KMZ, [and more](http://doc.arcgis.com/en/arcgis-online/create-maps/add-layers.htm)

Use this feature to add your own datasets. Shapefiles must be compressed in a zip archive (*.zip) before uploading. Browse for the file on your computer, then add it.

#####When a File Contains >1000 Features
You can't simply add upload files with >1000 features to your map. Instead, go to *MY CONTENT* and use the *Add Item* drop-down menu to upload the file from your computer. Once the file has been uploaded, return to your map and choose *Add | Search for Layers*, and look for the layer in My Content. Note that sometimes layers with >1000 features will render slowy, so you may want to filter them to show only a subset (see below for how!).

More details [here](http://doc.arcgis.com/en/arcgis-online/create-maps/add-layers.htm).
####Style Your Map
Click on the drop-down arrow next to a layer to see many options.
* **Change Style**: Choose an attribute/variable to show, then choose how you want to visualize the data (graduated symbols, colors, etc). Then click options to adjust the symbol type, color, and size. Click Done when you are happy with the result. Try out the settings to see how they work, or check out [the help](https://doc.arcgis.com/en/arcgis-online/create-maps/change-style.htm) for details.
* **Configure Pop-ups**: format the pop-up info windows, including which fields are visible. Try adding images or graphs! More details [here](http://doc.arcgis.com/en/arcgis-online/create-maps/configure-pop-ups.htm).
* **Display Images/Videos in Pop-Up Windows**: Your layer should have a column/variable containing a link to an image/video for each feature. You can then select this field under Pop-up Media when you’re configuring pop-ups.
* **Create Labels**: automatically add labels to your map.
* **Animate Your Map to Show Change Over Time**: if you have a [time-enabled](http://doc.arcgis.com/en/arcgis-online/create-maps/configure-time.htm) layer in your map, then you can use the timeline at the bottom of the map to adjust how the data are viewed. The civilwar_battles layer is time-enabled. If you *don't* wish to show the timeline, click on the drop-down arrow next to the layer and select *Disable Time Animation*.
* **Copy**: Copy a layer if you want to show multiple variables (for example, obesity in 2000 vs. 2010).

####Perform Analysis
Use built-in tools to perform basic spatial analysis (buffers, calculate distances, combine datasets, etc.)

Read [the help](http://doc.arcgis.com/en/arcgis-online/use-maps/perform-analysis.htm) for a detailed description of each tool...or just give them a try!

####Save & Share Your Map
**Regularly save your map (there’s no auto-save).** Click the *Save* menu at the top of the screen and give it a good name with at least one tag. It will be saved in *My Content*.

Use the *Share* button at the top of the screen to share your map.
* Share with the SocSci Bootcamp group so that others can see your map.
* Share the map via a link.
* Embed the map in a web site (must be shared with Everyone) or make a separate webapp. See the next section for details about making a webapp!
 
####Make a Story Map
Note: Creating a [story maps](http://storymaps.arcgis.com) is outside the time scope of this workshop, but it can result in very good-looking and informative maps (check out the gallery: http://storymaps.arcgis.com/en/gallery). Instructions are below in case you would like to give it a try on your own!

Decide what story you want to tell first. For example, if you're working on the Civil War project do you want to focus on all battles in a particular year? Only decisive battles? Battles in a particular area or involving particular commanders?

1.	Change the style of your data and filter it until it tells the story you would like. Save your map.
2.	Click Share, share your map with the SocSci Bootcamp group, then click the *Make a Web Application* button.
2.	For now, look under *Configurable Apps*. Hover over a template for details. Click *Publish* under a template, then either Preview or Publish it.
  * For something like a tour of Civil War sites, try the Story Map Journal or Story Map Tour. 
  * The Time Aware template allows you to animate change over time, but it can be buggy.
3.	After publishing the map, change the settings and appearance of the app. Click the *HELP* button at the top for tips. Each story map template is configured in a different way, so consult [the help](http://doc.arcgis.com/en/arcgis-online/create-maps/create-map-apps.htm) for more details about customizing each template.

---
###<a name="cartodbhead"></a>CartoDB     <http://cartodb.com/>
Go to the website to sign up for a free account. Chrome is the recommended browser for this tool.
####Add Data
**File formats:** CSV, Excel, ESRI Shapefiles, and GPX files

1. Go to your CartoDB dashboard (https://yourusername.cartodb.com/dashboard/)  and click *New Map* (the green button on the right side of the screen).
2. From here you can watch tutorials (highly recommended!) or create a new map from scratch. Choose Create New Map for now, and come back to watch the tutorials later.
3. Now you have several ways to bring in datasets. There is a built-in library of datasets or you can choose *Connect Dataset* to upload files to CartoDB. To add your own files:
  * Choose *Data file* to upload a dataset stored on your computer or the web. To upload a file, click the *Select a File* button near the bottom of the page. Shapefiles must be compressed in a zip archive (\*.zip) before uploading ([here's why](http://docs.cartodb.com/tutorials/import_shapefile_in_cartodb.html)). Click *Connect Dataset* to start the upload.
  * To import a dataset from a URL: Paste a URL to a data file into the *Enter a URL* field and click Submit. The URL should be to a supported file type. For example, if we want to import a layer showing libraries in MA from the MassGIS website, the .html URL for the [datalayer’s info page](http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/datalayers/libraries.html) won’t work; instead, we want the direct link to the libraries.zip file, which is the [*Download this layer: ESRI Shapefile* link](http://wsgw.mass.gov/data/gispub/shape/state/libraries.zip). ![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/massgis_libraries.jpg "MassGIS Data Site")
  * Additional help: http://docs.cartodb.com/tutorials/import_shapefile_in_cartodb.html

####Make a Map
#####View Your Data
  ![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_datamapview.jpg "2 views to work with data in CartoDB")

* **Map View**: Once you add data to your map, you will first see it as on a map. You may need to zoom or pan to it.

* **Data View**:  This shows you the variables for each feature (row) in the dataset as a spreadsheet. You can use this table view to format, query, and edit the data. It's a good idea to check that numbers are stored as numbers and not strings (text) at this point.

#####Style Your Data on the Map
Use the [tools in the sidebar](http://docs.cartodb.com/cartodb-editor.html#cartodb-sidebar) on the right side of the screen in Map View to change the appearance of the data in the map. 

![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_wizard.jpg "the style wizard") Start with the [Wizards tool] (http://docs.cartodb.com/cartodb-editor.html#wizards) to change the colors and size, or to make a chloropleth map. Within each way to style the data, you can change the appearance of it in the map. Try out the settings to see how they work, or check out [the help] (http://docs.cartodb.com/cartodb-editor.html#wizards) for details.

To animate the map to show change over time, you can use a tool called [Torque](http://docs.cartodb.com/tutorials/introduction_torque.html) that allows you to animate your data based on a numeric value. In the Wizard tool, find Torque. It will be automatically enabled in the Visualization wizard if you are working with a **point layer** such as the civil war battles (this tool  does not work for polygons or lines).

![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_infowindow.jpg "the info window tool") Next, change what shows up in the [info windows] (http://docs.cartodb.com/tutorials/infowindows.html) by clicking on the tool and adjusting which fields are visible. Note that info windows will be disabled if you are using Torque to animate the map.

#####Add Another Layer to the Map
Click the blue plus sign at the top of the right-hand toolbar to *Add layers* and then find the layer you want. You can select an existing layer or upload a new one. To create data within CartoDB (e.g., draw your own points, lines, or polygons), choose *Empty dataset* and then watch [this tutorial](http://docs.cartodb.com/tutorials/adding_geometries.html).

You can toggle between the layers in the right-hand toolbar to change how each is styled. [More details here](http://docs.cartodb.com/tutorials/multilayer_overview.html)

To remove a layer from your map, click on the small grey X next to the layer.

#####Add Map Elements
Click the *Add Element* button on the lefthand side of the screen. This allows you to add a legend, text box, annotation (linked to a particular location & zoom level), or image (e.g., a logo). Simply drag and drop to move them to the desired location, and click on an element to activate the formatting toolbar. Click [here] (http://docs.cartodb.com/cartodb-editor.html#add-element) for more details.

To change the background map, click *Change basemap* in the bottom left corner of the map. The *Options* button allows you to control whether additional map elements (legend, search box, share options, zoom controls, etc) are shown.

![alt text](https://raw.githubusercontent.com/cferwerda/NEASIST_workshop/master/img/cartodb_legend.jpg "the legend tool") To add a legend, use the [Legends tool] (http://docs.cartodb.com/cartodb-editor.html#legends) in the right-hand side bar. This is particularly useful if the colors on the map are meaningful (i.e., more than simple symbology) or your map shows multiple datasets.

####Share Your Map
Use the *Publish* button in the top-right corner to share your map. All maps are set as public for free CartoDB accounts -- if you want to make private maps, you'll need to pay to upgrade your account.

####Learn more about CartoDB
* [Use SQL to interact with, query, and edit your data.](http://docs.cartodb.com/tips-and-tricks.html#the-power-of-cartodb)
* [Tutorials](http://academy.cartodb.com/)
* [CartoDB Map of the Week](http://blog.cartodb.com/categories/map-of-the-week/)

---
###<a name="timemaphead"></a>TimeMapper  <http://timemapper.okfnlabs.org/>
*Note:* We didn't cover TimeMapper in the workshop, but it's a simple and handy tool to have in your kit.
To use TimeMapper, you need a Google account so that you can create a Google spreadsheet. Creating a TimeMapper account is optional, but it allows you to edit your maps later on.
####To learn how to use it:
*First*, watch the 1 minute tutorial on the website.

*Then* look at the example Civil War [spreadsheet](https://docs.google.com/spreadsheets/d/1E_r2WyxQmk7SNQhjeWBWz_R6Pv-DMe8kZjHb3TOM9GA/edit?usp=sharing) and [map](http://timemapper.okfnlabs.org/carolinferwerda/civil-war-battles-timemapper-example-spreadsheet).

*General steps:*

1. Decide what you want to focus on. (All battles in a particular year? Only decisive battles? Battles in a particular area or involving particular commanders?)
2. You can find a spreadsheet with all of the Civil War battles [here](https://docs.google.com/spreadsheets/d/1ZvMwypbUZeAwXZ6YPMVA-pRYLjAzmPA44nXUc4U-QA4/edit?usp=sharing). Create a new spreadsheet with the points of interest. Format the spreadsheet so that TimeMapper can read it. 
3. Find any additional media for each battles (an image or youtube video) and paste the link in the Media column of the spreadsheet. Fill in source information, descriptions, etc. This is the part where you can customize the message of the map!
4. Publish the map according to the instructions on the TimeMapper website. Share the link to your map with others!

---
## Data Sources
* **State and county outlines:** Global Administrative Areas database, <gadm.org>
* **US adult obesity by state:**  Centers for Disease Control and Prevention (CDC). Behavioral Risk Factor Surveillance System Survey Data. Atlanta, Georgia: U.S. Department of Health and Human Services, Centers for Disease Control and Prevention. <http://apps.nccd.cdc.gov/brfss/>
* **MA adult obesity:**  CDC, Diabetes Interactive Atlas, County Indicators, <http://www.cdc.gov/diabetes/atlas/countydata/County_ListofIndicators.html>
* **Population and census data:** US Census Bureau, American FactFinder, <https://factfinder2.census.gov/>
* **Civil War battle locations:** Robert Stewart, Jeremy Newcomb, and Chris Bunin. 2007. The Virginia Experiment. Data are restricted for educational purposes only. Downloaded from [ArcGIS Online](http://www.arcgis.com/home/item.html?id=e47e30d956d146498624f18b423a8f97). 
