---
layout: post
title:  "A Definitive Ranking of NZ's Council's GIS Viewers"
date:   2021-06-16
categories: misc
---
New Zealand is blessed with a lack of unification. A while ago it was decided that we should be split into regions, then districts. Regional and District Councils are an important part of our local government, representing the inhabitants in each region, mostly with diverse groups of white men. But do not fear, no matter where in the country you are, you will have representation through taxation thanks to your friendly regional GIS viewer. 

And these GIS viewers are important. The layperson can log in and make use of a friendly UI to find out property boundaries, gas lines, goverment valuations, flood risk and so on. And, far less importantly, my first introduction to GIS was through Auckland Council's GeoMaps. 

Creating this list was challenging. I will be using both Regional and District Councils. Lots of District Councils like to get ahead of themselves and act as Regional Councils - there are a fair few of what I can only assume are redundant ESRI contracts. Why do we have so many GIS viewers? I seek not to answer this question, but to celebrate the diversity we have the only way I know how: reading far too much into bad user interfaces and employment of open-source software.

Let's begin. Using the dreadfully outdated council maps on the [Local Government NZ website](https://www.lgnz.co.nz/local-government-in-nz/new-zealands-councils/) I tracked down each Regional Council and attempted to find its corresponding GIS viewer. I managed to find a GIS viewer for ecah region, save for Nelson and Tasman who kindly share. How does one evaluate such a complex and vital piece of digital infrastructure? Aribtrarily and with no mercy. All jokes aside, I am sure that each region is functioning well with their GISystems, so if I insult your locality please take my judgement with a tone of sarcasm - and please, hire me. 

**Testing Conditions**

Browser: Google Chrome 89.0.4389.72 64-bit

Operating System: Debian 10

Window Manager: i3

Browser Window Resolution: 1200 x 900

<h1>Summary</h1>
<p>
<table style="font-size:11px">
<colgroup>
<col width="15%" />
<col width="25%" />
<col width="30%" />
<col width="30%" />
</colgroup>
<thead>
<tr class="header">
<th>Council</th>
<th>Viewer Name and Link</th>
<th>Based on...</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">Northland</td>
<td markdown="span">[NRC Local Maps](https://localmaps.nrc.govt.nz/LocalMapsGallery/)</td>
<td markdown="span">LocalMaps (ESRI)</td>
<td markdown="span">Each map opens a unique session relating to chosen dataset</td>
</tr>
<tr>
<td markdown="span">Auckland</td>
<td markdown="span">[GeoMaps](https://www.aucklandcouncil.govt.nz/geospatial/geomaps/Pages/default.aspx)</td>
<td markdown="span">ArcGIS Dashboard (ESRI)</td>
<td markdown="span">Cool mesh of data. Take a look at traffic cameras</td>
</tr>
<tr>
<td markdown="span">Waikato</td>
<td markdown="span">[Property Viewer](https://maps.waikatodistrict.govt.nz/IntraMaps97/?project=Waikato&configId=b2549ae1-f643-4ac6-9586-211ba985dd8f#)</td>
<td markdown="span">IntraMaps 9 (TechnologyOne)</td>
<td markdown="span">Link is 'Property' collection. Look at [Waikato LASS Data Portal](https://data-waikatolass.opendata.arcgis.com/) (ArcGIS-based) for more</td>
</tr>
<tr>
<td markdown="span">Bay of Plenty</td>
<td markdown="span">[Bay eXplorer](https://gis.boprc.govt.nz/Html5/index.html?viewer=bayexplorer)</td>
<td markdown="span">GeoCortex (built on ArcGIS)</td>
<td markdown="span">More maps outside of BayeXplorer, but BayeXplorer is best</td>
</tr>
<tr>
<td markdown="span">Taranaki</td>
<td markdown="span">[Taranaki LocalMaps](https://maps.trc.govt.nz/LocalMapsGallery/)</td>
<td markdown="span">LocalMaps (ESRI)</td>
<td markdown="span"> </td>
</tr>
<tr>
<td markdown="span">Gisborne</td>
<td markdown="span">[Tair&#257;whiti Maps](https://maps.gdc.govt.nz/H5V2_12/)</td>
<td markdown="span">GeoCortex (built on ArcGIS)</td>
<td markdown="span"> </td>
</tr>
<tr>
<td markdown="span">Hawke's Bay</td>
<td markdown="span">[Maps & GIS](https://www.hbrc.govt.nz/services/maps-and-gis/)</td>
<td markdown="span">LocalMaps (ESRI)</td>
<td markdown="span">Other links show purpose-build maps, some of which are pretty good - see this [Hazard Portal](https://hbmaps.hbrc.govt.nz/hazards/)</td>
</tr>
<tr>
<td markdown="span">Wellington</td>
<td markdown="span">[GW Mapping](https://mapping.gw.govt.nz/)</td>
<td markdown="span">Based on ArcGIS Dashboard (ESRI)</td>
<td markdown="span">Linked is the really nice homepage, they also have an ArcGIS [data hosting site](https://data-gwrc.opendata.arcgis.com/)</td>
</tr>
<tr>
<td markdown="span">Nelson & Tasman</td>
<td markdown="span">[Top of the South Maps](https://www.topofthesouthmaps.co.nz/app/)</td>
<td markdown="span">ArcGIS Dashboard (ESRI)</td>
<td markdown="span">I like how they joined forces for this one, very cute. I wonder if they had to fight over whose name was displayed on the header first</td>
</tr>
<tr>
<td markdown="span">Marlborough</td>
<td markdown="span">[Smart Maps](https://maps.marlborough.govt.nz/smartmaps)</td>
<td markdown="span">LocalMaps (ESRI)</td>
<td markdown="span"> </td>
</tr>
<tr>
<td markdown="span">West Coast</td>
<td markdown="span">[WestMaps](https://gis.westcoast.govt.nz/WestMaps/)</td>
<td markdown="span">LocalMaps (ESRI)</td>
<td markdown="span"> </td>
</tr>
<tr>
<td markdown="span">Canterbury</td>
<td markdown="span">[Canterbury Maps Viewer](https://mapviewer.canterburymaps.govt.nz/)</td>
<td markdown="span">ArcGIS Dashboard (ESRI)</td>
<td markdown="span">A product of a bunch of District Councils. Also includes a basic ['3D' viewer](https://apps.canterburymaps.govt.nz/3dViewer-Beta/) (DEM with satellite imagery I suspect) </td>
</tr>
<tr>
<td markdown="span">Otago</td>
<td markdown="span">[Otago Maps](https://maps.orc.govt.nz/OtagoMaps/)</td>
<td markdown="span">LocalMaps (ESRI)</td>
<td markdown="span">They try and rebrand LocalMaps a bit. I wonder if they paid extra just to get their own splashscreen</td>
</tr>
<tr>
<td markdown="span">Southland</td>
<td markdown="span">[Southland District Maps](http://maps.southlanddc.govt.nz/Maps3/)</td>
<td markdown="span">Hexagon Geospatial (Intergraph)</td>
<td markdown="span">Uses leaflet which is cool. Barely works which isn't</td>
</tr>
</tbody>
</table>
</p>

<h1>Te Ika-a-M&#257;ui (North Island)</h1>

**NRC Local Maps (Northland Regional Council)**
Northland is right up the top of Te Ika-a-M&#257;ui, and with a local economy based mostly on agriculture and horticulture, I expected a good intreface wtith an abundance of VHR aerial imagery. NRC Local Maps (remember Local Maps, we will see it again) loads you up into a [browser of layers](https://localmaps.nrc.govt.nz/LocalMapsGallery/) as opposed to a GIS viewer per se. There are only 16 maps on display, and I suspect they are phasing into a new version of their GIS as some maps open one interface and some another.

<img style="width:100%" border=1 src="/assets/viewerrankings/northland.png">

Tools like draw and select are here, but barely. The user interface has this strangely annoying fade effect which makes it frustrating to navigate. Basemaps are that of a standard ESRI account. Panning is laggy but certainly useable, as with zooming. You can add layers from URL and/or file which is cool to see.

**Auckland Council**
https://www.aucklandcouncil.govt.nz/geospatial/geomaps/Pages/default.aspx

<img style="width:100%" border=1 src="/assets/viewerrankings/auckland.png">

**Waikato District Council**
https://maps.waikatodistrict.govt.nz/IntraMaps97/?project=Waikato&configId=b2549ae1-f643-4ac6-9586-211ba985dd8f

<img style="width:100%" border=1 src="/assets/viewerrankings/waikato.png">

**Bay of Plenty Regional Council**
https://maps.boprc.govt.nz/
I chose to evaluate the BayExplorer as, while it is designed for 'consultants and other professionals' (their words), it is an inclusive 'dashboard' rather than their individual map browsers.

<img style="width:100%" border=1 src="/assets/viewerrankings/bayofplenty.png">

**Taranaki Regional Council**
https://maps.trc.govt.nz/LocalMapsGallery/

<img style="width:100%" border=1 src="/assets/viewerrankings/taranaki.png">

**Gisborne District Council**
https://maps.gdc.govt.nz/H5V2_12/

<img style="width:100%" border=1 src="/assets/viewerrankings/gisborne.png">

**Hawke's Bay Regional Council**
https://www.hbrc.govt.nz/services/maps-and-gis/

<img style="width:100%" border=1 src="/assets/viewerrankings/hawkesbay.png">

**Greater Wellington Regional Council**
https://mapping.gw.govt.nz/

<img style="width:100%" border=1 src="/assets/viewerrankings/wellington.png">

<h1>Te Waipounamu (South Island)</h1>

**Nelson City Council/Tasman District Council**
https://www.topofthesouthmaps.co.nz/app/
why did they have to gender the google street view icon

<img style="width:100%" border=1 src="/assets/viewerrankings/nelsontasman.png">

**Malborough Regional Council**
https://maps.marlborough.govt.nz/smartmaps

<img style="width:100%" border=1 src="/assets/viewerrankings/marlborough.png">

**West Coast Regional Council**
https://gis.westcoast.govt.nz/WestMaps/

<img style="width:100%" border=1 src="/assets/viewerrankings/westcoast.png">

**Canterbury Regional/District(s) Council**
https://canterburymaps.govt.nz/

<img style="width:100%" border=1 src="/assets/viewerrankings/canterbury.png">

**Otago Regional Council**
https://orcportal.orc.govt.nz/portal/home/index.html

<img style="width:100%" border=1 src="/assets/viewerrankings/otago.png">

**Southland District Council**
http://maps.southlanddc.govt.nz/Maps3/

<img style="width:100%" border=1 src="/assets/viewerrankings/southland.png">
