# Kling-etal-People-Nature
This repository contains the (1) code, (2) results output, and (3) datasets used for a paper entitled "Provisioning services deline for both people and Critically Endangered wildlife in a rainforest transformation landscape."
Datasets include Appendix S1 (an Excel file that includes information on the provisioning services of all plants examined in the study) and the dataset used to model factors affecting botanical plot metrics for timber, medicinal plant, and ruffed lemur food tree provisioning services. Further details below:

The manuscript is under review with _People & Nature_, so this release has been labeled 'prepub' as a result. If accepted for publication, a further, final release will be published that includes the DOI for the manuscript, as well as any necessary updates to these materials.

DOI for the repository: 

<a href="https://zenodo.org/badge/latestdoi/638557972"><img src="https://zenodo.org/badge/638557972.svg" alt="DOI"></a>

Please contact me (Katherine!) with any comments or questions: katherine.kling@stonybrook.edu

# CODE & OUTPUT #
Includes R code (R Markdown) & results output (pdf of R Markdown output) for models analyzing effects of (a) distance & nearest community population and (b) change over time on plot metrics.

The code & output also include model visualizations to assist with interpretation.

# PLOTS.CSV #
This is the dataset used in the R code provided. The sheet contains the following columns...

$ plot.id: ID of each plot sampled

$ site: ID for each sampling location (_n_ = 13 communities, A-M; _n_ = 2 sampling locations within Masoala National Park (PA1, PA2)

$ year: year data were collected for plot

$ time: years since 2015, used in analyses

$ protected.area: binary Y/N of whether plot is in Masoala National Park; not used directly in modeling

$ pop: standardized population size of nearest community to plot; protected area plots were given population of 0

$ dist: standardized distance (m) of nearest community to plot

$ wood.ct: # of timber trees in plot

$ med.ct: # of individual medicinal plants in plot

$ lem.ct: # of trees that contain lemur food resources (i.e., lemur food trees) in plot

$ wood.rich: # of timber tree species in plot

$ med.rich: # of medicinal plant species in plot

$ lem.rich: # of lemur food tree species in plot

# APPENDIX S1 #
 Provisioning service(s) per plant
This appendix contains information on the provisioning services of 408 locally-identified plant ethnonyms located on the Masoala Peninsula, northeastern Madagascar, as well as the abundance of these plants, by type, across botanical plots sampled in 2015-2016. The appendix contains the following tabs:

(1) Key: A key to the appendix' contents

(2) Plant Provisioning Services: A data table that indicates whether each plant is (a) used by local communities, and, if so, for what purpose(s); and (b) consumed by the red-ruffed lemur (Varecia rubra), and, if so, what plant part(s) are consumed (i.e., fruit, flowers, and/or leaves)

(3) Abundance (tab for each plant provisioning service): Data tables for each provisioning service (i.e., timber) that (a) document the abundance of each species of that service (i.e., each timber species) across all botanical plots included in the study that were surveyed 2015-2016, as % individuals of species/ total individuals of service (i.e., % n Spp X timber trees/ total N timber trees); and (b) classifies each species as of 'High,' 'Medium,' or 'Low' abundance for each provisioning service

(4) High Abundance: Data table that provides statistics on provisioning service overlaps for all species that were indicated to be 'High' abundance for any given provisioning service

*Plant provisioning services for humans were documented for eight purposes: (1) timber (i.e., wood), (2) medicinal plants, (3) food, (4) alcohol production, (5) cordage, (6) weaving, (7) fodder for livestock, and (8) "other" purposes (with description incl.)

