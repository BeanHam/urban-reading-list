## Spatial Disaggregation

#### Bayesian Model
- **(2019)** [A spatial regression model for the disaggregation of areal unit based data to high-resolution grids with application to vaccination coverage mapping](https://journals.sagepub.com/doi/full/10.1177/0962280218797362)
  - **Abstract** This paper develops a methodology for high-resolution mapping of vaccination coverage using areal data in settings where point-referenced survey data are inaccessible.
  - **Model** Bayesian model: binomial spatial regression model with a logit link and a combination of covariate data and random effects modelling two levels of spatial autocorrelation in the linear predictor. The Bayesian model is fitted using the INLA-SPDE approach.
  - **Data**: DHS surveys from 2013 and 2015 in Afghanistan and Pakistan. Aggregated data at administrative level. 

- **(2019)** [Geospatial Disaggregation of Population Data in Supporting SDG Assessments: A Case Study from Deqing County, China](https://www.mdpi.com/2220-9964/8/8/356)
  - **Model** dasymetric method + grid census population into fine-resolution using 3d building information
  - **Data**: population data; building information; aerial images

#### Dasymetric Mapping
- **(2019)** [Spatial Disaggregation of Historical Census Data Leveraging Multiple Sources of Ancillary Information](https://www.mdpi.com/2220-9964/8/8/327)
  - nice literature review
  - **Model** a hybrid approach that combines pycnophylactic interpolation and regression-based dasymetric mapping
  - **Data**: CEDAR (11 geo regions); LOKSTAT (41 geo regions) + covariates

- **(2018)** [Spatially disaggregated population estimates in the absence of national population and housing census data](https://www.pnas.org/doi/pdf/10.1073/pnas.1715305115)
  - nice literature review

- **(2015)** [Disaggregating Census Data for Population Mapping Using Random Forests with Remotely-Sensed and Ancillary Data](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0107042)
  - **Model** dasymetric mapping + random fores

- **(2014)** [High resolution dasymetric model of U.S demographics with application to spatial distribution of racial diversity](https://www.sciencedirect.com/science/article/pii/S014362281400157X)
  - **Model** dasymetric model
  - **Data**: 
    - SEDAC (Socioeconomic Data and Ap- plications Center) 2000 U.S. Census Grids.
    - 17 demographic/socioeconomic characteris- tics + National Land Cover Dataset 2001
