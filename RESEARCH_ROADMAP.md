# Collazo Research Roadmap

## Objective

Build a defensible research identity in **Southeastern archaeology + GIS + remote sensing + reproducible methods** by producing real, citable outputs rather than portfolio filler.

## Research thesis

> How can geospatial computation, historical records, remote sensing, archaeological evidence, and reproducible analytical methods reconstruct, predict, understand, and protect cultural landscapes whose traces are difficult to see?

## Rules

1. Never fabricate data, fieldwork, affiliations, credentials, citations, results, or permissions.
2. Treat archaeological site locations, DoD/Army information, CUI, Tribal-sensitive information, employer data, and unpublished partner data as restricted unless explicitly cleared for release.
3. Prefer public, licensed, reproducible datasets for public research.
4. Every project must leave an audit trail: sources, code, provenance, decisions, limitations, and revision history.
5. Publication count is secondary to usefulness, reproducibility, and citation potential.

---

# Project 01 — Southeastern Predictive Archaeology Review

**Working title:** *Archaeological Predictive Modeling in the Southeastern United States: Methods, Validation, Bias, and Reproducibility*

### Why first

- Can be completed without restricted site coordinates.
- Establishes command of the literature before building models.
- Identifies what variables, validation practices, and failure modes need better research.
- Produces a literature database reusable by later papers.

### Outputs

- systematic/scoping review protocol
- searchable evidence table
- reproducible search log
- research-gap analysis
- preprint/manuscript draft
- conference poster or paper
- public explainer
- dataset of article/report metadata where licensing permits

### Questions

- Which environmental and cultural variables are most commonly used?
- How often do studies validate outside the training area?
- How common is spatial leakage?
- How are survey bias and negative evidence handled?
- How often is uncertainty reported?
- Which models actually outperform interpretable baselines?
- Which Southeastern physiographic regions remain methodologically understudied?

---

# Project 02 — Carolina Sandhills Open Geospatial Laboratory

**Working title:** *An Open Geospatial Workflow for Cultural-Landscape Analysis in the Carolina Sandhills*

Use only public and legally releasable layers for the public version.

### Candidate public inputs

- USGS elevation/DEM products
- publicly released LiDAR
- hydrography
- soils
- historic maps
- public transportation/history layers
- land-cover data
- historical aerial photography where licensed for use

### Methods

- terrain derivatives
- slope/aspect
- topographic position
- hydrological distance
- least-cost movement
- historical map georeferencing
- land-use change
- uncertainty maps

### Outputs

- Python/GeoPandas/Rasterio or ArcGIS-compatible workflow
- documented notebook(s)
- data provenance table
- maps
- reproducibility report
- methods manuscript

No sensitive archaeological locations belong in the public repository.

---

# Project 03 — Predictive Modeling Without the Black Box

**Working title:** *Prediction Is Not Explanation: A Reproducible Evaluation Framework for Archaeological Sensitivity Modeling*

### Core contribution

Compare simple interpretable baselines with more complex models while explicitly testing:

- spatial cross-validation
- class imbalance
- biased survey coverage
- calibration
- uncertainty
- feature importance stability
- transfer to new geographic areas

### Candidate models

- logistic regression
- generalized additive models
- random forest
- gradient boosting
- Bayesian/spatial approaches when justified

The goal is not to prove that machine learning is superior. The goal is to determine when added complexity produces genuine archaeological value.

---

# 12-Month Execution

## Months 1–2

- Establish ORCID and consistent professional name.
- Apply for appropriate early-career professional registration/associations where eligible.
- Create Zotero library and bibliographic database.
- Start Project 01 search protocol.
- Build the research evidence schema.
- Create researcher website skeleton and CV source-of-truth.
- Identify 20 researchers whose work overlaps with Southeastern archaeological GIS.

## Months 3–4

- Complete initial literature screening for Project 01.
- Extract methods and validation variables.
- Publish no conclusions until extraction is quality checked.
- Begin public-data inventory for Project 02.
- Prepare a small public-outreach/grant concept tied to archaeology + mapping.

## Months 5–6

- Draft Project 01 manuscript.
- Simulate two skeptical peer reviews.
- Contact a small number of genuine potential collaborators for methodological review.
- Produce first reproducible geospatial notebook for Project 02.
- Prepare conference abstract(s) when submission windows open.

## Months 7–9

- Submit or preprint Project 01 where appropriate and policy-compliant.
- Expand Project 02 into a complete, documented workflow.
- Produce a public map/story product with no sensitive site information.
- Prepare one institutional grant concept with a qualified partner.

## Months 10–12

- Draft Project 02 methods paper.
- Begin Project 03 benchmark framework.
- Present at a regional/national meeting if accepted.
- Apply for funding for the next stage.
- Update CV, ORCID, website, GitHub, and publication list from verified outputs only.

---

# Reputation Flywheel

Research question
→ evidence audit
→ reproducible data/code
→ manuscript
→ peer review
→ conference
→ public explanation
→ reusable dataset/tool
→ citations/collaboration
→ larger funded project

The target is not to look busy. The target is for another archaeologist to say: **“Use Collazo's workflow/data/review; it saves us time and holds up.”**
