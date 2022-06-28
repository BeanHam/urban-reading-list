## Spatial Disaggregation
- **(2019)** [A spatial regression model for the disaggregation of areal unit based data to high-resolution grids with application to vaccination coverage mapping](https://journals.sagepub.com/doi/full/10.1177/0962280218797362)
  - **Abstract** This paper develops a methodology for high-resolution mapping of vaccination coverage using areal data in settings where point-referenced survey data are inaccessible.
  - **Model** Bayesian model: binomial spatial regression model with a logit link and a combination of covariate data and random effects modelling two levels of spatial autocorrelation in the linear predictor. The Bayesian model is fitted using the INLA-SPDE approach.
  - **Data**: DHS surveys from 2013 and 2015 in Afghanistan and Pakistan. Aggregated data at administrative level. 

- **(2019)** [Geospatial Disaggregation of Population Data in Supporting SDG Assessments: A Case Study from Deqing County, China](https://www.mdpi.com/2220-9964/8/8/356)
  - **Model** dasymetric method + grid census population into fine-resolution using 3d building information
  - **Data**: population data; building information; aerial images


## Spatial Distribution Mapping
- **(2017)** [Mapping under-5 and neonatal mortality in Africa, 2000–15: a baseline analysis for the Sustainable Development Goals](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(17)31758-0/fulltext)
  - **Model** bayesian hierachical spatio-temporal model (SPDE)
  - **Data**: 1631 age record data; three other covariates

- **(2015)** [Fine resolution mapping of populationage-structures for health anddevelopment applications](https://royalsocietypublishing.org/doi/epdf/10.1098/rsif.2015.0073)
  - **Model** bayesian hierachical model
  - **Data**: data on child mortality and geographical locations from censuses and several household survey series, including the DHS, UNICEF Multiple Indicator Cluster Surveys, and other country-specific surveys. (n=59279) + covariates

- **(2014)** [High resolution dasymetric model of U.S demographics with application to spatial distribution of racial diversity]([https://royalsocietypublishing.org/doi/epdf/10.1098/rsif.2015.0073](https://www.sciencedirect.com/science/article/pii/S014362281400157X))
  - **Model** dasymetric model
  - **Data**: SEDAC 2000 U.S. Census Grids. + 17 demographic/socioeconomic characteris- tics + National Land Cover Dataset 2001
