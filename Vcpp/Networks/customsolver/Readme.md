## Custom solver

  <div xmlns="http://www.w3.org/1999/xhtml">This sample provides a custom ArcGIS Network Analyst extension solver for traversing a network dataset and finding connected/disconnected network components. </div>  


<!-- TODO: Fill this section below with metadata about this sample-->
```
Language:              VC++
Subject:               Networks
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
1. Open the solution file in Visual Studio.  
1. If your SDK is not installed in "\Program Files (x86)\ArcGIS\DeveloperKit10.2", search for that string and replace all entries with the correct path.  
1. Build the solution.  
1. If the compilation process does not register the CustomSolver.dll into ArcGIS Desktop, register it manually.  
1. Start ArcMap.  
1. Add a network dataset to the map.  
1. On the Network Analyst toolbar, click Network Analyst > Options, and set it to show all messages.  
1. Open the Network Analyst toolbar and click Network Analyst > New Connectivity.  
1. Load locations into the Seed Points layer of the Connectivity analysis layer.  
1. Click Solve. Lines are added to the Lines layer that reference source features that are not connected to any of the seed points.  
1. Right-click the Connectivity layer and click Properties to change the properties of the analysis layer, including whether you want to output the connected features instead of the disconnected features and whether or not you want to generate the line geometry.  
1. Re-solve to see the effects of changing the analysis layer properties.  









---------------------------------

#### Licensing  
| Development licensing | Deployment licensing | 
| ------------- | ------------- | 
| ArcGIS Desktop Basic | ArcGIS Desktop Basic: Network Analyst |  
| ArcGIS Desktop Standard | ArcGIS Desktop Standard: Network Analyst |  
| ArcGIS Desktop Advanced | ArcGIS Desktop Advanced: Network Analyst |  


