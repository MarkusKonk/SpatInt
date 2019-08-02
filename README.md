# Spatial interpolation using areal features: a review of methods and opportunities using new forms of data with coded illustrations
Coded examples in R of the different approaches described in the paper.

Alexis Comber<sup>1</sup>, Wen Zeng<sup>1</sup>,<sup>2</sup>

<sup>1</sup>School of Geography, University of Leeds, Leeds, LS2 9JT, UK. Email: a.comber@leeds.ac.uk

<sup>2</sup>Shandong University of Science and Technology, Qingdao, P.R. China. Email: alvin_z@163.com

## Abstract 
This paper provides a high level review of different approaches for spatial interpolation using areal features. It groups these into those that use ancillary data to constrain or guide the interpolation (dasymetric, statistical, street weighted and point-based), and those do not but instead develop and refine allocation procedures (area to point, pycnophylactic and areal weighting). Each approach is illustrated by being applied to the same case study. The analysis is extended to examine the the opportunities arising from the many new forms of spatial data that are generated by everyday activities such as social media, check-ins, websites offering services, micro-blogging sites, social sensing, etc, as well as intentional VGI activities, both supported by ubiquitous web- and GPS-enabled technologies. Here data of residential properties from a commercial website was used as ancillary data. Overall, the interpolations using many of the new forms of data perform as well as traditional, formal data, highlighting the analytical opportunities as ancillary information for spatial interpolation and for supporting spatial analysis more generally. However, the case study also highlighted the need to consider the completeness and representativeness of such data. The R code used to generate the data, to develop the analysis and to create the tables and figures is provided.

## Code 
The code and data used to illustrate a submission to Geography Compass. You can download the `SpatInt.R` file (`.Rmd` file to come...perhaps!) and run this in R or RStudio. It loads the `.RData` files and provides links to the `.R` files which describe how the data were created and assembled. You may need to install some of the packages but the code checks and does this. The script will load up the data (and different forms of ancillary data) and illustrate each of spatial interpolation approaches described in the text. Please contact me if you have queries! Lex (a.comber@leeds.ac.uk)

## Acknowledgements
This work was supported by the Natural Science Foundation of Shandong Province (ZR201702170310, the State Scholarship Fund of China Scholarship Council (201808370092) and the Natural Environment Research Council (NE/S009124/1). All of the analyses and mapping were undertaken in R 3.5.3 the open source statistical software.
