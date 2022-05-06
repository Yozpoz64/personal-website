---
layout: post
title: Past Projects
permalink: /portfolio/
---
Here you can find some examples of my work. To get the most recent projects I am working on, or some more in-depth information, send me an email or check out my GitHub :)

<h4>Modelling/ML/DL</h4>
I worked on a directed studies with Professor Giovanni Coco where we modelled extreme wave events in a section of beach in Torrey Pines, California. I used traditional machine learning (CNN, SVM) and deep learning in Python and Matlab to extract extreme wave events based on wave variables, then built a predictor from this dataset. 

Below is an example plot of the criteria for extreme wave events. When a threshold of beach width accretion/erosion was detected, the wave variables were extracted to add to the training dataset. As the dataset we based the predictor on was obtained privately I cannot post any plots of the actual modelling.

<p style="text-align: center;">
<img style="width:75%" border=1 src="/assets/portfolio/env390_example.png">
</p>

<h4>Segmentation for Cycling Pollutant Exposure Studies</h4>
For my final year project I developed spatial and temporal segmentation algorithms for pollution exposure measurements taken while cycling with Dr Katarzyna Sila-Nowicka. This will be to aid a future study of cyclists' pollution exposure and inhalation during cycle trips in Auckland. The following are some example plots that show how segmentation, and thus frequency of measurement, impacts modelled pollutant exposure.

<p style="text-align: center;">
<img style="width:75%" border=1 src="/assets/portfolio/m_selectedroutes.png">
</p>

<p style="text-align: center;">
<img style="width:75%" border=1 src="/assets/portfolio/p_bar_roads.png">
</p>

I did all of the analysis in ArcGIS Pro and Python. If I were to do it again, I would use PostGIS entirely. My main insight from this study was that these measurements need to be treated as a model. A measurement every 60 seconds is a simplification of reality, and need to be considered as such when performing analysis and drawing conclusions.


<h4>GeoLife Dashboard</h4>
For a Stage III GIS programming course I created a dashboard tool for looking at fine-grained mobility from the GeoLife dataset. You can access everything I worked on, including the code and project report, on my <a href="https://github.com/Yozpoz64/geolife-dashboard">GitHub</a>. Below is a short recording of me going through some random users:

<p style="text-align: center;">
<img style="width:85%" border=1 src="/assets/geolife/dashboardusage.gif">
</p>

<h4>Virtual Reality Development</h4>
The work I have done for VR systems and software is currently under a non-disclosure agreement. You can have a look at [this blog post](https://locative.dev/2021/03/03/My-Summer-VR-Locative-Reality/) I wrote earlier in 2021 about my time learning Unity and VR dev. I am also able to share this old dev video (I have since re-built the software from the ground-up):
<iframe width="100%" height="400" style="border:1px solid black;"
src="https://youtube.com/embed/BXkFA4CVcQw">
</iframe>

<h4>GIS/BIM/CAD Integration</h4>
I have limited experience translating CAD and BIM data into GIS formats to then be visualised. Typically I convert to GIS data in FME, then visualise in the AEC suite and/or Unreal Engine. That is an awful lot of acronyms I know, bear with me.

I really like the idea of automating this process to make easy visualisations with existing data. Take this basic model of Nelson I created with a LINZ DEM, DSM, building outlines and aerials.

![eoau](/assets/portfolio/nelson_model.jpg)

