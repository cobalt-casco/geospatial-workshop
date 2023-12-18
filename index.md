---
site: sandpaper::sandpaper_site
---

Data Carpentry's aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain. This modified version of the [DC geospatial curriculum](https://datacarpentry.org/lessons/#geospatial-curriculum) was made to serve the [Collaborative for Bioregional Action, Learning, and Transformation's Team Zoster](https://cobaltlearningjourney.com/team-zostera/) centered around the Casco Bay bioregion.


::::::::::::::::::::::::::::::::::::::::::  prereq

## Getting Started

Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to ensure the proper setup of tools for an efficient
workflow. To most effectively use these materials, please make sure to download
the data and install everything before working through this lesson.

This workshop assumes no prior experience with the tools covered in the workshop. However, learners with prior
experience working with geospatial data may be able to skip the
[Geospatial Project Organization and Management](https://cobalt-casco.github.io/organization-geospatial/) lesson.
Similarly, learners who have prior experience with the `R` programming language may wish to skip the
[Introduction to R for Geospatial Data](https://cobalt-casco.github.io/r-intro-geospatial/) lesson.

To get started, follow the directions in the [Setup](learners/setup.md) tab to
get access to the required software and data for this workshop.

::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::  prereq

## Data

The lessons in this workshop were originally developed through a hackathon funded by the
[National Ecological Observatory Network (NEON)](https://www.neonscience.org/) - an NSF funded observatory in Boulder, Colorado - in
collaboration with Data Carpentry, SESYNC and CYVERSE. NEON is collecting data for 30 years to help scientists understand
how aquatic and terrestrial ecosystems are changing. 

The data used in these lessons were collected to serve the COBALT Team Zostera's project in Casco Bay. They focus on either the state of maine or the Casco Bay area. Broadly, they come from two sources:

- [Landsat](https://landsat.gsfc.nasa.gov/) 8 and 9 data obtained from [USGS Earth Explorer](https://earthexplorer.usgs.gov/). Casco Bay is found in path 11 row 30 of the Landsat archive.

- Data from the [Maine GeoLibrary Data Catalogue](https://www.maine.gov/geolib/catalog.html). 

As the course gets closer, we will supply a link to download all of the data in one zip file.

These data files represent the teaching version of the data, with sufficient complexity to teach many aspects of  data analysis and
management, but with many complexities removed to allow students to focus on the core ideas and skills being taught.

| Dataset                      | File name                                                                                  | Description                                                                                                                                                                                                                                             | 
| ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Spatial boundaries and features of the state of maine       | maine_gov_maps.zip                                                              | A set of shapefiles for the maine featuring state boundaries, roads, and public boat launches.                                                                                                                                                   | 
| Seagrass data          | maine_gov_seagrass.zip                                                                | Polygon shapefiles of surveys of *Zostera marina* beds from either the state of Maine or just Casco Bay in 1997, 2010, 2013, 2018, and 2022.                                                                                                                                               | 
| Ocean turbidity | modis.zip                                                         | Data collected by MODIS characterizing the [Kd490](https://eastcoast.coastwatch.noaa.gov/cw_k490_hires.php) diffuse attentuation coefficient averaged over the summer of 2023. | 
| Landstat 8 and 9  raster data  | landsat_casco.zip                                                                   | 2013-2023 Landsat sea surface temperature data from the B10 thermal band cropped to Casco Bay from a day with minimal clouds between August and end of September. Also a full Landsat scene from August of 2023.                                                                                                      | 

[More information on this dataset](instructors/data.md)

::::::::::::::::::::::::::::::::::::::::::::::::::

# Workshop Overview

| Lesson                       | Overview                                                                                   | 
| ---------------------------------------------------------- | ------------------------------------------------------------ |
| [Introduction to Geospatial Concepts](https://cobalt-casco.github.io/organization-geospatial/)                             | Understand data structures and common storage and transfer formats for spatial data.       | 
| [Introduction to R for Geospatial Data](https://cobalt-casco.github.io/r-intro-geospatial)                             | Import data into R, calculate summary statistics, and create publication-quality graphics. | 
| [Introduction to Geospatial Raster and Vector Data with R](https://cobalt-casco.github.io/r-raster-vector-geospatial)                             | Open, work with, and plot vector and raster-format spatial data in R.                      | 

