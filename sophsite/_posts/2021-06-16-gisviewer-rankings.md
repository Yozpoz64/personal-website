---
layout: post
title:  "A Definitive Ranking of NZ's Council's GIS Viewers"
date:   2021-06-16
categories: misc
---
New Zealand is blessed with a lack of unification. A while ago it was decided that we should be split into regions, then districts. Regional and District Councils are an important part of our local government, representing the inhabitants in each region, mostly with diverse groups of white men. But do not fear, no matter where in the country you are, you will have representation through taxation thanks to your friendly regional GIS viewer. 

And these GIS viewers are important. The layperson can log in and make use of a friendly UI to find out property boundaries, gas lines, goverment valuations and flood risk. And, far less importantly, my first introduction to GIS was through Auckland Council's GeoMaps. 

Creating this list was challenging. I will be using both Regional and District Councils. Lots of District Councils like to get ahead of themselves and act as Regional Councils - there are a fair few of what I can only assume are redundant ESRI contracts. Why do we have so many GIS viewers? I seek not to answer this question, but to celebrate the diversity we have the only way I know how: reading far too much into bad user interfaces and employment of open-source software.

Let's begin. Using the dreadfully outdated council maps on the [Local Government NZ website](https://www.lgnz.co.nz/local-government-in-nz/new-zealands-councils/) I tracked down each Regional Council and attempted to find its corresponding GIS viewer. I managed to find a GIS viewer for ecah region, save for Nelson and Tasman who kindly share. How does one evaluate such a complex and vital piece of digital infrastructure? Aribtrarily and with no mercy. All jokes aside, I am sure that each region is functioning well with their GISystems, so if I insult your locality please take my judgement with a tone of sarcasm - and please, hire me. 

Testing conditions

Browser: Google Chrome 89.0.4389.72 64-bit

Operating System: Debian 10

Window Manager: i3

Browser Window Resolution: 1200 x 900

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

<h1>Summary</h1>
<table>
<colgroup>
<col width="20%" />
<col width="40%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th>Council</th>
<th>Viewer Name and Link</th>
<th>Based on...</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">Northland</td>
<td markdown="span">[NRC Local Maps](https://localmaps.nrc.govt.nz/LocalMapsGallery/)</td>
<td markdown="span">ArcGIS Dashboard (ESRI)</td>
</tr>

</tbody>
</table>