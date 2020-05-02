# IDCE 30262 Final Project - UNICEF in Kenya
The purpose of this project was to demonstrate how web mapping tools can support UNICEF's work and strengthen decision-making practices. This repository contains a mock HTML site for UNICEF hosting several web mapping products; these products address topics important to the organization's services and mission and are intended for various audiences and phases of the project cycle. The project page can be accessed [here.](https://spikeroot.github.io/IDCE_30262_unicef/index.html)

We chose to utilize an HTML site to tie these products together because it allows the data to be openly accessed by anyone with an internet connection. Though this does not necessarily mean universal access, it is an effective step in that direction. It also allows us to curate a polished environment for hosting and interacting with the data, facilitating the user experience. Though not all products are intended to be public-facing, we included them on this site for the purpose of presentation.

## Education
Kenya has made significant progress in increasing the accessibility of education, but there are still significant inequities in access, particularly among marginalized groups in nomadic and informal urban communities.

Several web mapping products were used within this project to display the dynamics of these inequities. The first is an ArcGIS Online (AGOL) dashboard created by Zoe Maymon. This dashboard presents a nuanced explanation of the distribution of both education access and overcrowding within classrooms, ideal for directing efforts during early decision-making phases. This would likely be an internal-facing map.

The second consists of two separate sliding comparison maps. These maps were created by Qidi Zhang using AGOL Story Map tools. Each map is meant to tell a story by juxtaposing two related datasets where they can be seen side by side. The first compares the distribution of population within Kenya with the distribution of those with primary education. The second compares the distribution of those with primary education against those with higher education, showing the striking concentration of the highly-educated populace around the capital region. These maps are meant to provide an example to the client of how data can be intuitively represented in a way that conveys complex phenomena.


## Healthcare
Kenya has made strides in reducing childhood mortality, but significant issues of healthcare access still exist.
The healthcare workforce is small and poorly distributed throughout the country, making it difficult for many to access services.

The map used in this project, created by Qi Zhang using Mapbox GL JS, displays both point locations of healthcare facilities within Kenya as well as a heatmap showing density of such facilities across the country. Using the slider, the data can be displayed side-by-side.

## Data Used
### Education
https://data.world/kenya-open-data/c5eda6b1-0d91-4fad-a493-31254b15db2a
https://hub.arcgis.com/datasets/66cfcf6d3724405bb15b0099faa46142_0
https://data.humdata.org/dataset/kenya-distribution-of-population-age-groups-3-years-and-above-by-school-attendance-status-special
https://data.humdata.org/dataset/kenya-distribution-of-population-aged-above-3-years-by-highest-level-of-education-reached
### Healthcare
https://data.world/healthsites/df79db22-da00-4c05-bda0-79c14f27132d

## Details and Attributions
All imagery acquired from Unicef.org, spatial data derived from the Humanitarian Data Exchange and Kenya Open Data. This project is not affiliated with UNICEF in any way - the 'Donate' link at the bottom of each page links to UNICEF's COVID relief fund.

## Limitations of Products
### Education
#### Data Dashboard:
-Limited in to the amount of visualizations you could add to the dashboard. Limited in the variety of widgets that can be added.
#### Data Sliders:
-With the current dataset, it is difficult to customize the slider format with shapefile features and without raster files. Current product limitation is the lack of detail attached to the web map without context surrounding it.
### Health care
#### Map Box Slider
-Limited in the amount of information that can be displayed between the map and the slider. Symbolic options are limited for the heat map creation.

## Potential Additions to Project
### Addition of Survey123 survey
Adding a Survey123 survey for the purpose of retrieving information, specifically for reporting poor classroom conditions, would be beneficial for future data that can be displayed on the website. Survey123 would be embedded in the website so the user of the website can fill out directly without being directed to another website. An ArcGIS web map would then be displayed on the same page displaying reports on the schools. Another potential survey can be displayed regarding healthcare, if the demand is there. 
### Adding More Narrative Elements to Website
Adding an about section with more information about the two subject matters would be beneficial to add more context behind the maps we are displaying. Displaying important datasources and narrative sources would be importatnt to list in order to provide reasoning for the work being done.
