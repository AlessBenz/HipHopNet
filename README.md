# Statistical Network Project - Music (Hip-hop) Network

This repository contains the R analysis for a music collaboration/artist network and links to an interactive Gephi visualization hosted in a separate repo.

## Repository structure
- **Data/raw/**: input datasets  
  - `edges.csv` - edge list  
  - `nodes.csv` - node metadata
- **reports/**: analysis report  
  - `Music_Project.Rmd` - source  
  - `Music_Project.pdf` - rendered output (if tracked)
- **gephi/**  
  - `index.html` - redirect to the interactive visualization

## How to run (RStudio)
1. Open `Statistical_Network_Project.Rproj`
2. Open `reports/Music_Project.Rmd`
3. Run chunks or knit to PDF

> If chunks run from `reports/` and paths fail, set RStudio to evaluate chunks in the **Project** directory (Tools → Global Options → R Markdown).

## Interactive visualization
Interactive network visualization:  
https://alessbenz.github.io/Gephi-hiphop-viz-network/network/

## Notes
- The visualization repo is the source of truth for the Gephi web export.
- This repo focuses on data preparation and analysis in R.
