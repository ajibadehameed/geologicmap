# geologicmap
This project provides a complete workflow for creating a geologic map of Nigeria and switzerland using QGIS, a free and open-source Geographic Information System. It demonstrates data acquisition, symbology design, geologic unit labeling, and final map layout export.

##  Workflow Steps

### Step 1: Set Up Project in QGIS
Launch QGIS and create a new project.

Set Project CRS to EPSG:4326 - WGS 84.

Save project as Nigeria_Geologic_Map.qgz.

### Step 2: Load and Prepare Data
Load Layers:

Nigeria administrative boundary (as a mask/clipping boundary).

Geologic unit polygons (e.g., from NGSA or USGS).

Clip Geologic Units:

Use Vector > Geoprocessing Tools > Clip to restrict data to Nigeria boundary.

### Step 3: Apply Geologic Symbology
Right-click the geologic layer → Properties → Symbology.

Choose Categorized symbology → Set column to Lithology or Formation.

Apply geologic color standards or use your own QML style file.

You can import a QML style via Style > Load Style.

For color reference: Follow the International Commission on Stratigraphy (ICS) or USGS color schemes.

### Step 4: Add Labels (Optional)
Right-click geologic layer → Properties → Labels tab.

Enable labels using the Formation Name or Rock Type field.

Customize font, size, and placement settings.

### Step 5: Add Map Elements
Use Layout Manager to create a printable/exportable map:

Insert Elements:

Map frame

Legend (filtered to only visible categories)

North arrow

Scale bar

Title and credits (e.g., “Geologic Map of Nigeria”)

Adjust map extent to focus on Nigeria.

### Step 6: Export the Map
In Layout Manager → Layout > Export as PDF/PNG/SVG

Set resolution (e.g., 300 dpi for print quality).

Save the map output to the exports/ folder.


## Maps produced

![Nigeria_Geology_Map_2](https://github.com/user-attachments/assets/d70e18ee-23a8-4138-bd9d-0c924a625e5b)

![switzerland_geology](https://github.com/user-attachments/assets/4cc94f91-8d7e-4e97-86a1-d36cb89bf34d)
