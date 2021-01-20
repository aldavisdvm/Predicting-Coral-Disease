# Predicting-Coral-Disease
Compares AdaBoost, Stacking, and XGBoost regressor models in predicting coral disease colonies
### Features used:

* FAC_CoralDiversity: Raw data for Coral Diversity: Diversity of hard corals. Expressed as the effective number
 of coral genera (exponential of the Shannon entropy index).
* FAC_CoralJuvDensity: Raw data for Juvenile Coral Density: Observed mean number of corals under 5 cm per square meter.
* FAC_HerbivorousFishBiomass: Raw data for Herbivorous Fish Biomass: Observed biomass of herbivorous fishes,
 grams per 100 meters square.
* FAC_MacroalgalCover_FishTeam: Raw data for Macroalgal Cover: Observed mean percent cover of macroalgae.
* FAC_BleachingResistance: Raw data for Bleaching Resistant Corals: Proportion of bleaching resistant coral species
 in an area, calculated from observed proportional abundance by species and observed patterns of bleaching by species.
* FAC_FishingDepletion: Raw data for Fishing Depletion: Percent depletion of reef fishes due to fishing mortality,
 calculated from differences between observed biomass and biomass expected in the absence of fishing pressure
 (Williams et al. 2015).
* FAC_TemperatureVariability: Raw data for Temperature Variability: History of high temperature variability in an area,
 calculated from the climatological summer temperature range divided by the annual temperature range (Heron et al. 2016).

### Methods Used

* Machine Learning
* Data Visualization
* Predictive Modeling
* AdaBoost Regressor
* Mlextend Stacking Regressor
* XGBoost Regressor

### Technologies

* Jupyter Notebook
* Python
* Pandas and Numpy
* Scikit-Learn
* Seaborn and Matplotlib

### Data was obtained from:

Oliver, Thomas A.; Kleiber, Danika; Hospital, Justin; Maynard, Jeffrey; Tracey, Dieter; 
Pacific Islands Fisheries Science Center (2020). Coral reef resilience and social vulnerability to climate change
 in the U.S.-affiliated Pacific Islands (NCEI Accession 0211010). NOAA National Centers for Environmental Information.

Dataset:
https://www.ncei.noaa.gov/archive/accession/0211010


## Project Summary

Data was explored, analyzed, and visualized. An AdaBoost Regressor was compared to an MlExtend Stacking Regressor
and an XGBoost Regressor using an mean squared error as measurement in the prediction of coral colony disease density.
An AdaBoost tree regression model had the lowest RMSE at 0.120,
with a stacked regressor with a RMSE of 0.121 very close behind. The XGBoost regressor, after cross validation
had an RMSE of 0.2637.
Coral diversity was the most important feature, followed by juvenile coral density in predicting
the number of diseased colonies of coral per square meter in this data set.


