# Crop mapping using fused optical-radar data set Data Set

<p align="center">
<img src="https://user-images.githubusercontent.com/90834830/182699400-f24d9810-0efc-4485-a623-f90155eb78c8.png">
</p>


Data Set Information:

This big data set is a fused bi-temporal optical-radar data for cropland classification. The images were collected by RapidEye satellites (optical) and the Unmanned Aerial Vehicle Synthetic Aperture Radar (UAVSAR) system (Radar) over an agricultural region near Winnipeg, Manitoba, Canada on 2012.
There are 2 * 49 radar features and 2 * 38 optical features for two dates: 05 and 14 July 2012.
Seven crop type classes exist for this data set as follows: 1-Corn; 2-Peas; 3- Canola; 4-Soybeans; 5- Oats; 6- Wheat; and 7-Broadleaf.


<p align="center">
<img width="537" alt="image" src="https://user-images.githubusercontent.com/90834830/182700052-4d014239-28cd-4888-b291-28761e7dba9c.png">
</p>


# Attribute Information:

<p>
175 attributes including:

<li>class</li>
<li>f1 to f49:Polarimetric features on 05 July 2012</li>
<li>f50 to f98:Polarimetric features on 14 July 2012</li>
<li>f99 to f136:Optical features on 05 July 2012</li></li>
<li>f137 to f174:Optical features on 14 July 2012</li>
</p>

Goal:

To identify/estimate the appropriate crop mapping for the 7 crops which are 1-Corn; 2-Peas; 3- Canola; 4-Soybeans; 5- Oats; 6- Wheat; and 7-Broadleaf over an agricultural region near Winnipeg, Manitoba, Canada.

# Steps:

<li>Loading Dataset and using basic functions on the dataset</li>

<img src="https://user-images.githubusercontent.com/90834830/182702576-aa90d4b5-4ed1-469b-80aa-3c9b8e35a405.png">

<li>Summary Statistics and Describe Command</li>

<img src="https://user-images.githubusercontent.com/90834830/182702851-5ace8eb5-9572-48e4-8b37-1a62878f9bdb.png">

<li>Corr Command</li>

<img src="https://user-images.githubusercontent.com/90834830/182703692-cb1bf301-e8f6-4b0c-b514-61c61a05c424.png">

<p align="center">
<img width="314" alt="image" src="https://user-images.githubusercontent.com/90834830/182704430-757568e5-1b47-4bdf-8074-8dcda7492092.png"></p>

<li>Feature Engineering</li>

<li>Removing unwanted rows and columns</li>

<li>Data Visualization</li>

<li>Line Chart</li>

<img src="https://user-images.githubusercontent.com/90834830/182704957-385ad4a1-9e40-4a2b-a613-81b5cc38c0bb.png">

<li>Scatter Plot</li>

<img src="https://user-images.githubusercontent.com/90834830/182705160-b272e117-dae3-4d1a-99bc-31e90cb876e5.png">

<img src="https://user-images.githubusercontent.com/90834830/182705265-796968f1-7e86-41a0-8072-0142d74c9d8d.png">


<li>Histogram</li>

<img src="https://user-images.githubusercontent.com/90834830/182705355-748676e4-d16b-4336-ab25-2850961bd82f.png">

<li>Bar Chart</li>

<img src="https://user-images.githubusercontent.com/90834830/182705537-6762bf46-f522-4ec6-a150-5562a00233a6.png">

<li>Density Plot</li>

<img src="https://user-images.githubusercontent.com/90834830/182705621-53dee9cc-b1be-4735-a50d-ea394edcebcb.png">

<li>Kernel Density Plot</li>

<img src="https://user-images.githubusercontent.com/90834830/182705634-0c3768bb-8db6-4d87-82e2-d5398e685875.png">

<li>Applying Algorithm</li>

<img src="https://user-images.githubusercontent.com/90834830/182705701-d8a8fca7-6b07-4b4f-9ad0-58b93100fc89.png">
