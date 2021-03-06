## Buffer snap agent

  <div xmlns="http://www.w3.org/1999/xhtml">
    <span class="PropertyValue">This sample demonstrates how to create a snapping agent based on a buffer around the points of the current editable point feature class. In this sample, a snapped vertex of a feature is located no closer than 1000 map units from the point that is closest to the cursor. For electrical datasets, it is common to want to snap primary lines to the boundary of the symbol representing a pole. Use this snapping agent with an appropriate buffer distance (based on the radius of the pole symbol).</span>
  </div>  


<!-- TODO: Fill this section below with metadata about this sample-->
```
Language:              C#, VB
Subject:               Controls
Organization:          Esri, http://www.esri.com
Date:                  11/17/2017
ArcObjects SDK:        10.6
Visual Studio:         2015, 2017
.NET Target Framework: 4.5
```

### Resources

* [ArcObjects .NET API Reference online](http://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm)  
* [Sample Data Download](../../releases)  
* [What's new](http://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#91cabc68-2271-400a-8ff9-c7fb25108546.htm)  
* [Download the ArcObjects SDK for .Net from MyEsri.com](https://my.esri.com/)  

### Usage
1. Open and build the solution to register the BufferSnap class in the ESRI Engine Snap Agents component category.  
1. Run the solution.  
1. Start editing.  
1. Zoom in on some point features to a 1:30000 map scale.  
1. Open the Snapping Environment dialog box and turn on the Buffer Snap agent.  
1. Begin adding new features to snap to buffers (1000 map units) around the point features in the specified feature class.  









---------------------------------

#### Licensing  
| Development licensing | Deployment licensing | 
| ------------- | ------------- | 
| Engine Developer Kit | ArcGIS Desktop Basic |  
|  | ArcGIS Desktop Standard |  
|  | ArcGIS Desktop Advanced |  
|  | Engine |  


