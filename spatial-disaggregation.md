## Spatial Disaggregation

#### 1. Mass-Preserving areal weighting/areal interpolation: 
the known population of an administrative zone is distributed uniformly across its area. This process happens on a discretized grid over an administrative zone, where each cell in the grid is assigned a population value equal to the total population over the total number of cells that cover an administrative zone.

#### 2. Pycnophylactic Interpolation 

#### 3. Dasymetric Mapping: 
Dasymetric weighting schemes extend this idea of distributing the known population of an area by creating a weighted surface to distribute the known population, instead of doing so uniformly. The weighting schemes are determined by combining different spatial layers (e.g., slope, average rainfall, land/water masks) according to some set of rules. While some weight- ing schemes are completely ad-hoc, recently, machine learning methods have been used to improve upon this approach. These methodologies are similar to traditional supervised machine learning problems, but since actual ground truth data does not exist to compare against, val- idating the results of dasymetric models is challenging.

- **(2019)** [Spatial Disaggregation of Historical Census Data Leveraging Multiple Sources of Ancillary Information](https://www.mdpi.com/2220-9964/8/8/327)
  - nice literature review
  - **Model** a hybrid approach that combines pycnophylactic interpolation and regression-based dasymetric mapping
  - **Data**: CEDAR (11 geo regions); LOKSTAT (41 geo regions) + covariates

- **(2018)** [Spatially disaggregated population estimates in the absence of national population and housing census data](https://www.pnas.org/doi/pdf/10.1073/pnas.1715305115)
  - nice literature review

- **(2015)** [Disaggregating Census Data for Population Mapping Using Random Forests with Remotely-Sensed and Ancillary Data](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0107042)
  - **Model** dasymetric mapping + random fores

- :tada: **(2014)** [High resolution dasymetric model of U.S demographics with application to spatial distribution of racial diversity](https://www.sciencedirect.com/science/article/pii/S014362281400157X)
  - **Model**: dasymetric model
  - **Data**: 
    - SEDAC (Socioeconomic Data and Applications Center) 2000 U.S. Census Grids: gridded population count, demographic, socioeconomic varables.
    - Auxillary data: NLCD (National Land Cover Dataset) 2001: The idea of dasymetric modeling is to redistribute the total population count within a cell into its constituent sub-cells using NLCD information. We use two different types of NLCD information for dasymetric modeling.

#### 4. Deep Learning
- **(2017)** [A Deep Learning Approach for Population Estimation from Satellite Imagery](https://dl.acm.org/doi/10.1145/3149858.3149863)
  - **Model**: CNN
  - **Data**: 
    - population data: 2002 census data for Tanzania (18421 areas) and 2009 census data for Kenya (7150 areas).
    - satellite data: Landsat 7 1-year composite images for 2000 and 2010

- **(2016)** [Equitable development through deep learning: The case of sub-national population density estimation](https://dl.acm.org/doi/10.1145/3001913.3001921)
  - **Model**: CNN
  - **Data**: 
    - population data: Center for International Earth Science Information Networks’ (CIESIN) US Census Summary Grids for 2000 and 2010
    - satellite data: LANDSAT 7 mission images + Defense Meteorological Satellite Program Operational Line Scanner
----
#### 5. Bayesian Model
- **(2019)** [A spatial regression model for the disaggregation of areal unit based data to high-resolution grids with application to vaccination coverage mapping](https://journals.sagepub.com/doi/full/10.1177/0962280218797362)
  - **Model**: Bayesian model: binomial spatial regression model with a logit link and a combination of covariate data and random effects modelling two levels of spatial autocorrelation in the linear predictor. The Bayesian model is fitted using the INLA-SPDE approach.
  - **Data**: DHS surveys from 2013 and 2015 in Afghanistan and Pakistan. Aggregated data at administrative level. 

- **(2019)** [Geospatial Disaggregation of Population Data in Supporting SDG Assessments: A Case Study from Deqing County, China](https://www.mdpi.com/2220-9964/8/8/356)
  - **Model**: dasymetric method + grid census population into fine-resolution using 3d building information
  - **Data**: population data; building information; aerial images
