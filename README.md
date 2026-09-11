# Mapping and Spatial Analysis in R

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22710469.svg)](https://doi.org/10.5281/zenodo.22710469)

An introductory tutorial on mapping and spatial data analysis in **R**, developed for the **UCL R User Group**.

The tutorial introduces the main concepts and tools needed to work with spatial data in R, from understanding spatial data structures and coordinate reference systems through to mapping, spatial operations, raster analysis and introductory spatial statistics.

## Tutorial

The rendered tutorial is available here:

**https://yangjustinc.github.io/2025-mapping-and-spatial-analysis-in-r/**

An alternative version is also available on RPubs:

**https://rpubs.com/yangjustinc/mapping-and-spatial-analysis-in-r-2025**

The archived v1.0.0 release is available from Zenodo: **https://doi.org/10.5281/zenodo.22710469**.

## What the tutorial covers

The tutorial includes:

* the fundamentals of spatial data and spatial thinking;
* vector and raster data models;
* coordinate reference systems;
* importing and manipulating spatial data;
* static and interactive mapping;
* spatial joins and other spatial operations;
* spatial relationships, proximity and adjacency;
* raster and elevation analysis;
* spatial autocorrelation;
* hotspot analysis;
* spatial interpolation; and
* reproducible workflows for spatial research.

Examples and exercises are included throughout to demonstrate how the techniques can be applied to practical research questions.

## Who is this for?

The tutorial is intended for researchers and analysts who:

* have some basic familiarity with R;
* are new to spatial analysis, or want a refresher on its core concepts; and
* want to learn how to incorporate geographic information into their research.

No previous experience with GIS or spatial analysis is required.

## R packages

The tutorial primarily uses the modern R spatial ecosystem, including:

* [`sf`](https://r-spatial.github.io/sf/) for vector spatial data;
* [`terra`](https://rspatial.github.io/terra/) for raster data;
* [`tmap`](https://r-tmap.github.io/tmap/) for thematic mapping;
* [`leaflet`](https://rstudio.github.io/leaflet/) for interactive maps;
* [`ggplot2`](https://ggplot2.tidyverse.org/) and [`dplyr`](https://dplyr.tidyverse.org/) for visualisation and data manipulation;
* [`rnaturalearth`](https://docs.ropensci.org/rnaturalearth/) for example geographic data;
* [`spdep`](https://r-spatial.github.io/spdep/) for spatial dependence and autocorrelation; and
* [`gstat`](https://r-spatial.github.io/gstat/) for geostatistics and spatial interpolation.

## Repository contents

* [`mapping-and-spatial-analysis-in-r.qmd`](./mapping-and-spatial-analysis-in-r.qmd) — source Quarto document
* [`mapping-and-spatial-analysis-in-r.html`](./mapping-and-spatial-analysis-in-r.html) — rendered tutorial
* [`references.bib`](./references.bib) — bibliography
* [`styles.css`](./styles.css) — custom styling
* [`_extensions/`](./_extensions/) — Quarto extensions used by the tutorial
* [`mapping-and-spatial-analysis-in-r.Rproj`](./mapping-and-spatial-analysis-in-r.Rproj) — RStudio project

## Running the tutorial locally

Clone the repository:

```bash
git clone https://github.com/yangjustinc/2025-mapping-and-spatial-analysis-in-r.git
cd 2025-mapping-and-spatial-analysis-in-r
```

Open the RStudio project and install the principal packages if required:

```r
install.packages(c(
  "sf",
  "terra",
  "tmap",
  "leaflet",
  "dplyr",
  "ggplot2",
  "rnaturalearth",
  "spdep",
  "gstat",
  "spatstat"
))
```

The Quarto document can then be rendered with:

```bash
quarto render mapping-and-spatial-analysis-in-r.qmd
```

## Further learning

The tutorial draws on and points readers towards several excellent resources for more advanced spatial analysis, including:

* [Geocomputation with R](https://r.geocompx.org/)
* [Spatial Data Science with R](https://r-spatial.org/book/)
* [R for Spatial Analysis](https://rspatial.org/r4spatial/)
* [Geographic Data Science with R](https://geographicdata.science/book/)

## Author

**Justin C. Yang**
University College London
