# IDCE 30262 Final Project - UNICEF in Kenya
The purpose of this project was to demonstrate how web mapping tools can support UNICEF's work and strengthen decision-making practices. This repository contains a mock HTML site for UNICEF hosting several web mapping products; these products address topics important to the organization's services and mission and are intended for various audiences and phases of the project cycle. The project page can be accessed [here.](https://spikeroot.github.io/IDCE_30262_unicef/index.html)

We chose to utilize an HTML site to tie these products together because it allows the data to be openly accessed by anyone with an internet connection. Though this does not necessarily mean universal access, it is an effective step in that direction. It also allows us to curate a polished environment for hosting and interacting with the data, facilitating the user experience. Though not all products are intended to be public-facing, we included them on this site for the purpose of presentation.

## Education
Kenya has made significant progress in increasing the accessibility of education, but there are still significant inequities in access, particularly among marginalized groups in nomadic and informal urban communities.

Several web mapping products were used within this project to display the dynamics of these inequities. The first is an ArcGIS Online (AGOL) dashboard created by Zoe Maymon. This dashboard presents a nuanced explanation of the distribution of both education access and overcrowding within classrooms, ideal for directing efforts during early decision-making phases. This would likely be an internal-facing map.

The second consists of two separate sliding comparison maps. These maps were created by Qidi Zhang using AGOL Story Map tools. Each map is meant to tell a story by juxtaposing two related datasets where they can be seen side by side. The first compares the distribution of population within Kenya with the distribution of those with primary education. The second compares the distribution of those with primary education against those with higher education, showing the striking concentration of the highly-educated populace around the capital region. These maps are meant to provide an example to the client of how 


## Healthcare(Product3)
**Prototypes Discussion:

Kenya has made strides in reducing childhood mortality, but significant issues of healthcare access still exist.
The healthcare workforce is small and poorly distributed throughout the country, making it difficult for many to access services.

The map used in this project, created by Qi Zhang using Mapbox GL JS, displays both point locations of healthcare facilities within Kenya as well as a heatmap showing density of such facilities across the country. Using the slider, the data can be displayed side-by-side.

This product can help UNICEF to make decisions. Finding areas with less health conditions from the map can help UNICEF to provide targeted humanitarian assistance.There are relatively few health data in Kenya, and Health facilities point data is the most worthy of showing. Because UNICEF can clearly understand the distribution of health facilities, which can effectively help UNICEF to select areas that need help.

Product3 used Mapbox GL JS to make a slidable map. It is a good way to show both maps. Mapbox is powerful and the map is beautiful and concise. Sliding the map is very interesting. This product can display two kinds of maps well, and the heat map makes up for the problem that the points are too dense to see. The limitation is that there is less interaction, and too little health data can be found in Kenya, which limits the type of map.

**Considerations on surveys / mobile data collection：

Using Mapbox to update data is very convenient, you can easily upload new data and display, you can use the original map link, no need to change the code.

**Data:

The data is a point data in Shapefile format downloaded from DATA WORLD. It contains the location, name and type of 1,350 health facilities in Kenya. [LINK](https://data.world/healthsites/df79db22-da00-4c05-bda0-79c14f27132d)

## Details and Attributions
All imagery acquired from Unicef.org, spatial data derived from the Humanitarian Data Exchange and Kenya Open Data. This project is not affiliated with UNICEF in any way - the 'Donate' link at the bottom of each page links to UNICEF's COVID relief fund.

## Potential Additions to Product
