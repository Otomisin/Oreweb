---
title: "Here are some of my works"
# author: "Oluwatosin Orenaike"
output: 
  html_document :
    toc: yes
    theme: flatly
    toc_float: yes
    keep_md: yes
---

<hr>
# ```{r setup, include=FALSE}
# knitr::opts_chunk$set(echo = FALSE)
# library(gridExtra)
# library(knitr)
# ```

<!-- ## ArGIS Online -->
<!-- <iframe src="https://www.arcgis.com/apps/mapviewer/index.html?webmap=f2c20e15bd7a430a9bd24b8413291b97" width="100%" height="500"></iframe> -->

<hr>
<hr>


## Leaflet Map Showing Captial of African Countries
# ``` {r}
# library(leaflet)
# library(gridExtra)
#
# # Generate random data points
# set.seed(123)
# n_points <- 50
# data <- data.frame(
#   lon = runif(n_points, -180, 180),
#   lat = runif(n_points, -90, 90),
#   value = rnorm(n_points, 50, 10)
# )
#
# # Create leaflet map
# leaflet(data) %>% addTiles() %>%
#   addMarkers(~lon, ~lat, popup = ~paste("Value: ", value))
#
# ```


## Static Maps 
### Arctic Sea Ice decline made from a turoral
![**Context:** Arctic Sea Ice decline made from a turoral. <br> **Tools**: ArcGIS Pro <br>**Date:** 2023](images/Arctic.png)
<hr>

### Displacement Map
![**Context:** Displacement Map. <br> **Tools**: ArcGIS Pro <br>**Date:** 2023](images/idps.png)
<hr>
### DTM Map
![**Context:** DTM Map. <br> **Tools**: ArcGIS Pro <br>**Date:** 2023](images/Worldv8.png)
<hr>

![**Context:** Arctic Sea Ice decline made from a turoral. <br> **Tools**: ArcGIS Pro <br>**Date:** January 2023](images/PPG3.png)
<hr>

### Map of Papua New  Guinea
![**Context:** Arctic Sea Ice decline made from a turoral. <br> **Tools**: ArcGIS Pro <br>**Date:** January 2023](images/SSD4.png)
<hr>

### Map of Vanuatu
![**Context:** Arctic Sea Ice decline made from a turoral. <br> **Tools**: ArcGIS Pro <br>**Date:** January 2023](images/Vanuatu6.png)
