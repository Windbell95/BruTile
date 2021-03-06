[![Build status](https://ci.appveyor.com/api/projects/status/5s4poobpfab9g8ny?svg=true)](https://ci.appveyor.com/project/pauldendulk/brutile)
[![NuGet Status](http://img.shields.io/nuget/v/BruTile.svg?style=flat)](https://www.nuget.org/packages/BruTile/)
[![NuGet pre-release status](http://img.shields.io/nuget/vpre/BruTile.svg?style=flat)](https://www.nuget.org/packages/BruTile/)

### BruTile
BruTile is a C# open source library to access tile services like OpenStreetMap and Bing. BruTile has few dependencies, is platform independent and has a limited scope. It is intended for reuse by other more sophisticated libraries

### Getting Started

Take a look [here](https://github.com/BruTile/BruTile/wiki/Getting-Started-with-BruTile)

### Demo
For a demo download the source code and run BruTile.Demo in the Samples folder

### BruTile 2.0 (prerelease) as .NET Standard
BruTile 2.0 supports .NET Standard. The Profiles by NuGet package:

| Library                  |   Targeted Framework  |
| ------------------------ | --------------------- |
| BruTile                  |  .NET Standard 1.1    |
| BruTile.MbTiles          |  .NET Standard 1.1    |
| BruTile.Desktop          |  .NET Standard 1.6    |
| BruTile.Desktop.DbCache  |  .NET Standard 2.0    |

All these libraries additionally target .Net Framework 4.5

### BruTile 1.0 as Portable Class Library (PCL)
BruTile 1.0 has been released as a PCL with Profile111. This profile targets: .Net Framework 4.5, ASP.NET Core 5.0, Windows 8, Windows Phone 8.1, Xamarin.Android, Xamarin.iOS, Xamarin.iOS (Classic).

### Supported tile service protocols:
* [WMTS](http://www.opengeospatial.org/standards/wmts)
* [TMS](https://wiki.osgeo.org/wiki/Tile_Map_Service_Specification)
* [OSM](http://wiki.openstreetmap.org/wiki/Slippy_map_tilenames) (Like TMS with inverted y-axis)
* [WMS](http://www.opengeospatial.org/standards/wms) (tiled requests to a regular WMS)
* [ArcGIS Tile Server](http://resources.arcgis.com/en/help/rest/apiref/tile.html)
* [WMS-C](https://wiki.osgeo.org/wiki/WMS_Tile_Caching#WMS-C_as_WMS_Profile)

### Roadmap
- Stability of v1 and v2 is currently our primary focus.

### Projects that use BruTile

* [ArcBruTile](https://github.com/arcbrutile/arcbrutile/) a plugin for ArcGIS
* [SharpMap](https://github.com/SharpMap/SharpMap) a GIS library
* [Mapsui](https://github.com/pauldendulk/Mapsui) a MapComponent for Xamarin.Android. Xamarin.iOS, UWP and WPF
* [DotSpatial](https://dotspatial.codeplex.com/) a GIS library that is used in [HydroDesktop](https://hydrodesktop.codeplex.com/)
* [PDOK](https://www.pdok.nl/nl/producten/pdok-software/pdok-extensie-voor-arcgis) extensie voor ArcGIS

### License
[Apache 2.0](https://raw.githubusercontent.com/BruTile/BruTile/master/LICENSE.md)
