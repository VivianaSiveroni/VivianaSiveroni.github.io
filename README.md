# My Portfolio

Below are examples of my work in ArcGIS, Archaeology, Databases and more.

[Cartography and Spatial Analysis in ArcGIS](#Cartography and Spatial Analysis in ArcGIS)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Black and White Maps](#black-and-white-maps)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[DEMs](#dems)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Landsat 7 images](#landsat-7-images)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Feature digitisation and Classification](#feature-digitisation-and-classification)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Llama (*Llama glama*) GIS](#Llama (*Llama glama*) GIS)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[DEM display and HILLSHADE](#dem-display-and-hillshade)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Ortho-mosaics and digitised features](#ortho-mosaics-and-digitised-features)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[TIN creation](#tin-creation)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Google Earth and Google Maps as background](#google-earth-and-google-maps-as-background)






## Cartography and Spatial Analysis in ArcGIS
### Black and White Maps 
This map was produced for a publication that demanded complex data in b/w format. Three data frames are used to locate the study area (bottom) and display the main features at the local (centre) and regional (top) levels.

![image alt](images/Caravans_Fig1_w_arrow_mod2.jpg?raw=true)


### Integrating DEMs
A simple map of the region of Nasca, Peru incorporating a DEM downloaded from INGEMMET (Peru). Inset uses data from the same source but represents political administrative units.

![image alt](images/Ch2_TheDrainage_characteristics_mod.jpg?raw=true)


### Landsat 7 Images
This map is based on Landsat 7 imagery with reassigned bands (band combination 4, 3, 2) to show the vegetation's extent (in red) in the Nasca area.

![image alt](images/Landsat8_2017_April_Nasca_location_mod.jpg?raw=true)


### Feature Digitisation and Layer Symbology
This map shows features from an excavation in Peru. Most features were directly mapped in the field using a GPS/Total Station, the data was stored in a data collector and then transferred to Autocad. Others were digitised from ortho-mosaics produced in the field. Later, features were imported into ArcGIS. In addition, some small features were produced by digitising paper drawings and images that were georeferenced using ground points. 

![image alt](images/Ch4_Cluster4_Middle_Map12_mod.jpg?raw=true)

### Llama (*Llama glama*) GIS
This illustration shows the ubiquity of llama bones in the excavations of Huayuri. The llama skeleton is a Llama GIS where each skeletal specimen (i.e., bone) appears black if the record is NOT NULL. In addition, this illustration is an example of the deployment of five data frames simultaneously.
 
![image alt](images/LlamaGis_by_HH_mod.jpg?raw=true)
 

### DEM Display and HILLSHADE
A topographic map of Huayuri archaeological site (Peru). The elevation model was built from points taken directly in the field with a Total Station. “Lines” illustrating walls were created by digitising an Ortho-mosaic (architecture) into ArcGIS. The display of the topography is achieved using two superimposed layers. The top layer is the original DEM with transparency ca. 40%, and the bottom one is a DEM processed using the HILLSHADE tool. 

![image alt](images/HUAY_ARCH_SURFACE_for_neighb11_mod.jpg?raw=true)
 
### Ortho-mosaics and Digitised Features
The central data frame displays an ortho-mosaic created in PCI Geomatica years ago using 5MP images taken from an ultralight plane during a low-height flight. Ground points were used to georeferenced the final image. If you zoom in you will be able to see the blue crosses that mark ground control points. The other data frames in the plate show the location of the main frame in the ravine where the site is located (left) and the location of the excavation units (right).

![image alt](images/CompoundC03_ExcUnits_mod.jpg?raw=true)

### TIN Creation
A TIN was created in ArcGIS using the centre  of postholes as vertices as a way to represent possible roof structures across the excavated area and the likely length of beams that supported the roof. Polygons representing postholes were created by georeferencing paper drawings (using sewing pins as ground control points!) that were later digitised.

![image alt](images/Ch5_Dist_Middle_Roof_PostholeSize_mod.jpg?raw=true).

### Google Earth and Google Maps as Background
This simple illustration uses Google Earth Imagery to locate archaeological sites and their main surface features. Inset uses grids in the border to locate the site using UTM coordinates.

![image alt](images/Ch3_Cahuachi_mod.jpg?raw=true).

### Spatial Analysis
Calculation of time of travel from Huayuri (archaeological site) to different features in the landscape. This map was achieved by running Tobler’s hiking function in the Spatial Analyst extension (Path Distance Tool).

![images alt](images/HuayuriCostDistance_mod.jpg?raw=true)

### Image Analysis
Calculation of Normalised Difference Vegetation Index to display strong healthy vegetation (High = 1). This map was achieved with the Band Arithmetic function within the Image Analysis window. 

![image alt](images/LandCover_mod.jpg?raw=true)

### Classification by Area
Architectural Units within an archaeological site are classified by area. Other archaeological features are displayed to understand the function of structures based on artefact association.

![image alt](images/PINCH_ARCH_SURF_neighb5_mod.jpg?raw=true)
