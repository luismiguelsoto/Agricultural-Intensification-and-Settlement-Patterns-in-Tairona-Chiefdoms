Agricultural Intensification and Settlement Patterns in Tairona Chiefdoms (AD 100–1600): A Multi-Scalar Study of the House-Lot Model in the Sierra Nevada de Santa Marta (under review)
--------------------------------------------------------------

This repository contains code and data for a multi-scalar analysis of residential spatial organization and agricultural intensification. It applies the house-lot model to evaluate how agricultural soil quality structured settlement patterns. The analysis utilizes soil suitability proxies and spatial analysis of stone-terrace structures to test positive covariation between infield potential and exterior activity areas. The protocol is applied to three chronological periods in the Río Frío basin (Sierra Nevada de Santa Marta): Neguanje, Buritaca, and Tairona.

Repository Structure:
----------------------------------
1. GIS:
   - Contains the spatial data files (shapefile components and raster files) defining the study area:
     • POLYGON_RIO_FRIO_UTM_Polygons.shp
     • SITES_RIO_FRIO_TAIRONA_PERIOD_UTM_polygons.shp
     • SOIL_SUITABILITY_RASTERS.tif (and associated auxiliary files)

2. R Code Files:
   - The main R script (or R Markdown file) contains the code to:
     a) Load required packages.
     b) Download the datasets and GIS files directly from GitHub.
     c) Process environmental variables and perform House-Lot spatial analysis.
     d) Generate the figures or tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.5.2]
- Key R packages used in this project include (with version numbers):
    •  dplyr: version 1.1.4
    •  ggplot2: version 4.0.0
    •  ggspatial: version 1.1.10
    •  ineq: version 0.2-13
    •  patchwork: version 1.3.2
    •  purrr: version 1.1.0
    •  raster: version 3.6-32
    •  sf: version 1.0-21
    •  sp: version 2.2-0
    •  spatstat.explore: version 3.5-3
    •  spatstat.geom: version 3.6-0
    •  stats: version 4.5.1
    •  terra: version 1.8-60
    •  tidyr: version 1.3.1
    •  viridis: version 0.6.5

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the code or contact the corresponding author.

Manuscript Summary:
----------------------------------
This study applies Killion's house-lot model to evaluate how agricultural soil quality structures residential spatial organization in Tairona chiefdom communities of the Río Frío basin, Sierra Nevada de Santa Marta, Colombia (AD 100-1600). Using soil suitability to proxy infield potential and available space between stone-terrace structures to proxy maintained exterior activity area, the analysis tests whether the predicted positive covariation holds across three chronological periods. During Neguanje and Buritaca, structures on higher-quality soils maintained larger available spaces, supporting the infield agriculture model. In the Tairona period, nearly sevenfold demographic expansion compressed exterior space uniformly and reversed this pattern, regardless of soil quality. Multi-scalar analysis revealed that household-level spatial gradients dissolved while landscape-level soil preference strengthened, indicating that intensification and settlement nucleation sent divergent signals across analytical scales. These findings contribute an additional neotropical chiefdom case to comparative discussions of how demographic growth reshapes residential landscapes through terrace investment, coordination, and differentiated land use.

For questions or further information, please contact: lms313@pitt.edu
