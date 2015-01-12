## DATA
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
* Find other layers at [MassGIS] (http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/datalayers/) 

####Tornadoes, 1950-present
* tornadoes3.zip – point shapefile (zipped) of locations of all tornadoes of at least a magnitude of 3 on the EF-scale, 1950-2013
* tornado.zip at <http://www.spc.noaa.gov/gis/svrgis/> – line shapefile of tracks of all tornadoes (magnitudes 1-5), 1950-2013
* Tornado Variable Descriptions.pdf – metadata for the tornado datasets
* CountyPop2010.zip – polygon shapefile (zipped) of county outlines with population information

#####Data Sources
* **State and county outlines:** Global Administrative Areas database, <gadm.org>
* **US adult obesity by state:**  Centers for Disease Control and Prevention (CDC). Behavioral Risk Factor Surveillance System Survey Data. Atlanta, Georgia: U.S. Department of Health and Human Services, Centers for Disease Control and Prevention. <http://apps.nccd.cdc.gov/brfss/>
* **MA adult obesity:**  CDC, Diabetes Interactive Atlas, County Indicators, <http://www.cdc.gov/diabetes/atlas/countydata/County_ListofIndicators.html>
* **Population and census data:** US Census Bureau, American FactFinder, <https://factfinder2.census.gov/>
* **Civil War battle locations:** Robert Stewart, Jeremy Newcomb, and Chris Bunin. 2007. The Virginia Experiment. Data are restricted for educational purposes only. Downloaded from [ArcGIS Online] (http://www.arcgis.com/home/item.html?id=e47e30d956d146498624f18b423a8f97). 


## TOOLS
###TimeMapper  <http://timemapper.okfnlabs.org/>
To use TimeMapper, you need a Google account so that you can create a Google spreadsheet. Creating a TimeMapper account is optional, but it allows you to edit your maps later on.
####To learn how to use it:
*First*, watch the 1 minute tutorial on the website.

*Then* look at the example Civil War [spreadsheet] (https://docs.google.com/spreadsheets/d/1E_r2WyxQmk7SNQhjeWBWz_R6Pv-DMe8kZjHb3TOM9GA/edit?usp=sharing) and [map] (http://timemapper.okfnlabs.org/carolinferwerda/civil-war-battles-timemapper-example-spreadsheet).
*General steps:*
1. Decide what you want to focus on. (All battles in a particular year? Only decisive battles? Battles in a particular area or involving particular commanders?)
2. Create a new spreadsheet with the battles of interest. Format the spreadsheet so that TimeMapper can read it.
3. Find any additional media for each battles (an image or youtube video) and paste the link in the Media column of the spreadsheet. Fill in source information, descriptions, etc. This is the part where you can customize the message of the map!
4. Publish the map according to the instructions on the TimeMapper website.

---
###ArcGIS Online  <https://www.arcgis.com/home/signin.html>
You will be provided with temporary accounts during the workshop. The accounts will remain available to you until 1/21, after which all content will be deleted as these accounts will be used in other trainings.
####Add Data
#####Upload Data
#####Search for Data on ArcGIS Online
####Make a Map

---
###CartoDB  <http://cartodb.com/>
Go to the website to sign up for a free account.

Chrome is the recommended browser for this tool.
####Add Data
**File formats:** CSV, Excel, ESRI Shapefiles, and GPX files
1. Go to your CartoDB dashboard (https://yourusername.cartodb.com/dashboard/)  and click *New Table* (the big plus sign in the right side of the screen).
2. Now you have several ways to bring in datasets. Two commonly used options:
⋅⋅* Upload Data: Shapefiles must be compressed in a zip archive (*.zip) before uploading. Choose *select a file* or drag and drop the zip file onto the New table window. () 
⋅⋅* Import from URL: Paste a URL to a data file into the field. The URL should be to a supported file type. For example, if we want to import a layer showing libraries in MA from the MassGIS website, the URL for the datalayer’s info page (http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/datalayers/libraries.html) won’t work; instead, we want the link to the libraries.zip file, which is from *Download this layer: ESRI Shapefile* (http://wsgw.mass.gov/data/gispub/shape/state/libraries.zip).
⋅⋅* Additional help: http://docs.cartodb.com/tutorials/import_shapefile_in_cartodb.html
