This repository contains materials for the "**Unsupervised classification (clustering) of satellite images**"
workshop on [OpenGeoHub Summer School 2023](https://opengeohub.org/summer-school/opengeohub-summer-school-poznan-2023/).

# Introduction

Unsupervised classification of satellite images is the process of grouping similar pixels on an image
into homogeneous clusters based primarily on their spectral characteristics. This approach does not
require reference (labeled) data, unlike supervised classification, therefore it can be used as a method
of first choice. Satellite image classification is commonly used in a variety of fields, including
environmental monitoring, land cover mapping, and disaster management. The thematic maps generated
can be used to identify and monitor changes in land use, and assess the impact of natural disasters.

# Requirements

**Skills**

The workshop is aimed at beginners, but basic knowledge of R programming, GIS and satellite remote sensing
is required. If you want to expand your knowledge, I highly recommend the following materials:

1. Article "[What is Remote Sensing?](https://www.earthdata.nasa.gov/learn/backgrounders/remote-sensing)"
by National Aeronautics and Space Administration
2. Book "[Geocomputation with R](https://r.geocompx.org/)" by Robin Lovelace, Jakub Nowosad and Jannes Muenchow
(in particular chapters 2.3 and 4.3)
3. Book "[Spatial Data Science with R and “terra”](https://rspatial.org/)" by Robert Hijmans et at.

**Software**

You need to install [R](https://cloud.r-project.org/), [RStudio](https://posit.co/download/rstudio-desktop/)
and required packages in this way:

```r
install.packages(c("terra", "tidyr", "ggplot2"))
```

The documentation for the `terra` package can be found here: https://rspatial.github.io/terra/reference/terra-package.html

**Hardware**

Your computer should have a minimum of 8 GB of RAM.

# Materials &#128681;

You will find the necessary data on Google Drive or Zenodo. After downloading, the data should be unpacked.

You can download interactive notebooks (*.Rmd*) and static documents (*.html*) from this repository:

1. [Unsupervised classification](https://kadyb.github.io/OGH2023/Clustering.html)
2. [Task](https://kadyb.github.io/OGH2023/Task.html)

The description of spectral bands can be found [here](https://landsat.gsfc.nasa.gov/satellites/landsat-8/landsat-8-bands/).

# Contact

If you have any questions or need help, please let me know at [Mattermost](https://mattermost.opengeohub.org/)
or email me (krzysztof.dyba@amu.edu.pl).
