# gdal-docker
[![dockeri.co](http://dockeri.co/image/webmapp/gdal-docker)](https://hub.docker.com/r/webmapp/gdal-docker/)  

GDAL Docker container with AWSCLI, read/write support for file geodatabases via ESRI File Geodatabase API 1.5 and Microsoft ODBC 13.1 driver with SQLCMD and BCP.  

## Tags
Each stable GDAL release has a corresponding tag. GDAL trunk is built nightly from  
the Github master branch and is available on the `latest` tag

## Formats
The following formats are supported:
```
PCIDSK -raster,vector- (rw+v): PCIDSK Database File
netCDF -raster,vector- (rw+s): Network Common Data Format
PDF -raster,vector- (w+): Geospatial PDF
ESRI Shapefile -vector- (rw+v): ESRI Shapefile
MapInfo File -vector- (rw+v): MapInfo File
UK .NTF -vector- (ro): UK .NTF
OGR_SDTS -vector- (ro): SDTS
S57 -vector- (rw+v): IHO S-57 (ENC)
DGN -vector- (rw+): Microstation DGN
OGR_VRT -vector- (rov): VRT - Virtual Datasource
REC -vector- (ro): EPIInfo .REC
Memory -vector- (rw+): Memory
BNA -vector- (rw+v): Atlas BNA
CSV -vector- (rw+v): Comma Separated Value (.csv)
GML -vector- (rw+v): Geography Markup Language (GML)
GPX -vector- (rw+v): GPX
KML -vector- (rw+v): Keyhole Markup Language (KML)
GeoJSON -vector- (rw+v): GeoJSON
OGR_GMT -vector- (rw+): GMT ASCII Vectors (.gmt)
GPKG -raster,vector- (rw+vs): GeoPackage
SQLite -vector- (rw+v): SQLite / Spatialite
ODBC -vector- (rw+): ODBC
WAsP -vector- (rw+v): WAsP .map format
PGeo -vector- (ro): ESRI Personal GeoDatabase
MSSQLSpatial -vector- (rw+): Microsoft SQL Server Spatial Database
PostgreSQL -vector- (rw+): PostgreSQL/PostGIS
OpenFileGDB -vector- (rov): ESRI FileGDB
FileGDB -vector- (rw+): ESRI FileGDB
XPlane -vector- (rov): X-Plane/Flightgear aeronautical data
DXF -vector- (rw+v): AutoCAD DXF
Geoconcept -vector- (rw+): Geoconcept
GeoRSS -vector- (rw+v): GeoRSS
GPSTrackMaker -vector- (rw+v): GPSTrackMaker
VFK -vector- (ro): Czech Cadastral Exchange Data Format
PGDUMP -vector- (w+v): PostgreSQL SQL dump
OSM -vector- (rov): OpenStreetMap XML and PBF
GPSBabel -vector- (rw+): GPSBabel
SUA -vector- (rov): Tim Newport-Peace's Special Use Airspace Format
OpenAir -vector- (rov): OpenAir
OGR_PDS -vector- (rov): Planetary Data Systems TABLE
WFS -vector- (rov): OGC WFS (Web Feature Service)
HTF -vector- (rov): Hydrographic Transfer Vector
AeronavFAA -vector- (rov): Aeronav FAA
Geomedia -vector- (ro): Geomedia .mdb
EDIGEO -vector- (rov): French EDIGEO exchange format
GFT -vector- (rw+): Google Fusion Tables
SVG -vector- (rov): Scalable Vector Graphics
CouchDB -vector- (rw+): CouchDB / GeoCouch
Cloudant -vector- (rw+): Cloudant / CouchDB
Idrisi -vector- (rov): Idrisi Vector (.vct)
ARCGEN -vector- (rov): Arc/Info Generate
SEGUKOOA -vector- (rov): SEG-P1 / UKOOA P1/90
SEGY -vector- (rov): SEG-Y
XLS -vector- (ro): MS Excel format
ODS -vector- (rw+v): Open Document/ LibreOffice / OpenOffice Spreadsheet
XLSX -vector- (rw+v): MS Office Open XML spreadsheet
ElasticSearch -vector- (rw+): Elastic Search
Walk -vector- (ro): Walk
Carto -vector- (rw+): Carto
AmigoCloud -vector- (rw+): AmigoCloud
SXF -vector- (ro): Storage and eXchange Format
Selafin -vector- (rw+v): Selafin
JML -vector- (rw+v): OpenJUMP JML
PLSCENES -raster,vector- (ro): Planet Labs Scenes API
CSW -vector- (ro): OGC CSW (Catalog  Service for the Web)
VDV -vector- (rw+v): VDV-451/VDV-452/INTREST Data Format
TIGER -vector- (rw+v): U.S. Census TIGER/Line
AVCBin -vector- (ro): Arc/Info Binary Coverage
AVCE00 -vector- (ro): Arc/Info E00 (ASCII) Coverage
HTTP -raster,vector- (ro): HTTP Fetching Wrapper
```
