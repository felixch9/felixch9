# Project 001 — Archaeological Predictive Modeling in the Southeastern United States

## Working title
Archaeological Predictive Modeling in the Southeastern United States: Methods, Validation, Bias, and Reproducibility

## Core question
How have archaeological predictive models in the southeastern United States been built, validated, and interpreted, and where do survey bias, pseudo-absence construction, spatial autocorrelation, and non-spatial validation create avoidable overconfidence?

## Why this matters
Predictive models are widely used in archaeological research and cultural-resource management, but model performance can be distorted when known-site inventories reflect where archaeologists have surveyed rather than where archaeological sites actually occur. The project therefore separates **prediction** from **explanation** and treats validation design as a first-order methodological issue.

## Initial verified anchor literature
The initial search has already identified a South Carolina lineage spanning early predictive/probabilistic modeling, model validation, GIS-based landscape modeling, and more recent geostatistical work. It also identified broader methodological literature showing that random validation can overstate performance when archaeological data are spatially autocorrelated.

South Carolina / Southeast anchors include:
- Canouts (1981), *Predictive Modeling: An Archeological Assessment of Duke Power Company's Proposed Cherokee Transmission Lines* — SCIAA Research Manuscript Series 173.
- Canouts (1981), *Woodland Occupation in the Upper Coastal Plain of South Carolina* — SCIAA Research Manuscript Series 174.
- O'Donoughue (2008), *Living in the Low Country: Modeling Archaeological Site Location in the Francis Marion National Forest, South Carolina* — MA thesis.
- Scurry (2015), *Validation of a Prehistoric Woodland Period Site-Settlement Model for the Coastal Plain of South Carolina*, *Southeastern Geographer* 55(1):70–101. DOI: 10.1353/sgo.2015.0006.
- Gillam (2016), *Multivariate Analysis and Geographic Modeling of Archaeological Landscapes* — University of South Carolina dissertation.
- Gillam (2016), *Archaeological Predictive Modeling along the Central Savannah River*, *Legacy* 20(1):22–25.
- Coughlan & Nelson (2019), *Geostatistical analysis of historical contingency and land use footprints in the prehistoric settlement dynamics of the South Carolina Piedmont, North America*, *Journal of Archaeological Science* 107:1–9. DOI: 10.1016/j.jas.2019.04.003.

Broader methodological anchors include:
- Wachtel et al. (2018), comparison of logistic regression and MaxEnt for archaeological site prediction.
- Yaworsky et al. (2020), GLM/GAM/MaxEnt/random-forest comparison and explicit discussion of pseudo-absence and sampling problems. DOI: 10.1371/journal.pone.0239424.
- Comer et al. (2023), demonstration that sampling strategy and spatial autocorrelation alter measured archaeological predictive-model performance. DOI: 10.1016/j.jasrep.2022.103824.
- Amazonian archaeological machine-learning work using blocked spatial cross-validation rather than ordinary random folds.

## Primary review dimensions
Every included study should be coded, where possible, for:
- geography and archaeological context
- data source and sample design
- environmental and cultural predictors
- presence/absence/pseudo-absence construction
- survey-bias handling
- spatial autocorrelation
- train/test design
- random vs spatial cross-validation
- external validation
- calibration and uncertainty
- model family
- interpretability
- performance metrics
- reproducibility/code/data availability
- stated limitations
- prediction vs explanatory claims

## Current hypothesis — NOT YET A CLAIM
A potentially important research gap is that southeastern U.S. archaeological predictive modeling may contain a long, rich applied tradition but inconsistent treatment of survey bias, spatial leakage, pseudo-absence construction, calibration, and reproducible validation. This must be tested, not assumed.

## Safety / ethics
This project must not publish protected archaeological coordinates, non-public ArchSite data, Army/DoD information, CUI, employer-owned data, or Tribal-sensitive information. Public review work should rely on published and legally accessible sources.

## Status
Literature discovery and protocol construction are in progress. No results or novelty claim should be considered final until evidence extraction is sufficiently complete and audited.
