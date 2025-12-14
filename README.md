# Global-Earthquakes-2020-2025

Aim: To Analyze the Significant Seismic Events of Magnitude 4.5+ detected 
by the USGS (United States Geological Survey) from 
January 1, 2020, to December 10, 2025.
Data Provider: USGS Earthquake Hazards Program.

Data: 

Downloadlink : Download the Dataset from the website www.kaggle.com 
Global Earthquakes 2015 - 2025 : 10 years of Data

Steps:  Open the csv file. It contained data of a data with 84000+ Records.
Select Data from 2020 to 2025. Save it as earthquake.xlsx. 
OPen the earthquake.xlsx sheet. Select the columns which gives information for analysis
Latitude -	The latitude of the earthquake's epicenter, reported in decimal degrees(North/South).
Longitude -	The longitude of the earthquake's epicenter, reported in decimal degrees(East/West).
Depth  -	  Depth of the earthquake in kilometers (km).
mag	-       The magnitude of the earthquake, reported on various magnitude scales
magType -	  The magnitude type used to report the earthquake magnitude (e.g. "mb", "ml", "mw").
time	-     UTC Timestamp of the event (to the millisecond).
place -	    A human-readable description of the earthquake's location
Dmin:       The distance to the nearest station in degrees.

Save the xlsx file. 

Open the file from PowerBI Desktop . Home -> Get Data -> Excel workbook.

Check for the Datatypes. As the Excelworkbook has only a sheet, Relatioship mapping is not required.

Cleaning and Transforming the Data.
Go to the Query Editor, click on Transform Data Icon. 
Select Transform Data. 
Double click on each column and view the column statistics. 
Remove any Errors, Duplicates or Empty Records. Refresh.
Click Close and Apply Button.

From the left Hand  Side, Select the Table view and analyze the changes.

Creating Visualizations
Select the Report View.
FRom the Visualizations pane, select the charts to display the date/time, Geographical Locations and Magnitude.
Add the data to the Visualization Field. Add the Title 
Magnitude Of Earthquake by Year and Month

Publish the report by clicking on publish Button and select publish to PowerBI
Login to PowerBi and View the interactive visualization .
Magnitude Of Earthquake by Year and Month. Select year and month and view the different Seismic Locations on map.

