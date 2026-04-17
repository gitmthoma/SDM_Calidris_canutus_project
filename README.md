📍 Species Distribution Modeling of Calidris canutus

This project models the seasonal distribution of the Red Knot (Calidris canutus) along the East Atlantic Flyway using species distribution models (SDMs).

🌍 Objectives
Model breeding, stopover, and wintering distributions
Compare current vs. future climate scenarios (SSP1-2.6, SSP5-8.5)
Evaluate the influence of ecological predictors on stopover habitats

🧠 Methods
Occurrence data: GBIF
Environmental predictors: WorldClim, CHELSA
Models: GLM, GAM, Random Forest, GBM, MAXNET (ensemble approach)
Validation: AUC, TSS, spatial cross-validation

📊 Key Results
Strong range expansion in breeding areas under climate change
Decline in suitability for stopover habitats
Ecological predictors improve stopover model performance

⚙️ Reproducibility
Data is not included due to size. Required datasets:

WorldClim v2.1
CHELSA climate data
GBIF occurrence data

🚧 Status
This is an ongoing project. 

Planned extensions:
inclusion of tidal flat extent and NDVI
improved stopover habitat modeling
refinement of seasonal classification
