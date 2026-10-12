# One Piece Metadata Analytics

An R-based data analytics project exploring *One Piece* episode and character metadata using REST APIs, JSON parsing, and exploratory data analysis. The project investigates saga progression, episode distribution, and story arc duration trends, with analysis documented using R Markdown.

## Overview

This project applies data collection and preprocessing techniques to anime metadata to explore the structure and progression of *One Piece*. Data retrieved from a REST API is parsed, cleaned, and organized into structured datasets for further analysis.

<img width="596" height="356" alt="Screenshot 2026-10-12 124504" src="https://github.com/user-attachments/assets/a3a1f8fe-89e8-400e-8fd9-f6a2b6d318bb" />


## Objectives

- Retrieve and parse JSON metadata from a REST API. (https://www.api-onepiece.com/)
- Transform raw API responses into structured datasets.
- Clean and preprocess data for analysis.
- Examine episode distribution across sagas and story arcs.
- Explore trends in story arc duration and saga progression.

## Technologies

- **R** — Data processing and analysis
- **REST APIs** — Metadata retrieval
- **JSON** — Data parsing and transformation
- **R Markdown** — Reproducible analysis and reporting
- **HTML** — Rendered analytical report
- **Git & GitHub** — Version control

## Repository Structure

| File | Description |
|---|---|
| `Strawhats_Report.Rmd` | Main R Markdown analysis report |
| `Strawhats_Report.html` | Rendered HTML report containing the analysis |
| `projectPrez.Rmd` | Project presentation source |
| `projectPrez.html` | Rendered project presentation |
| `project-workshop-inclass.Rmd` | Supporting workshop material |
| `final-project-strawhats.Rproj` | RStudio project configuration |
| `.gitignore` | Specifies files excluded from version control |
| `.github/` | GitHub repository configuration and workflows |

## Getting Started

### Prerequisites

- [R](https://cran.r-project.org/)
- [RStudio](https://posit.co/download/rstudio-desktop/)

### Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/johnesparragoza/one-piece-metadata-analytics.git
   ```

2. Open `final-project-strawhats.Rproj` in RStudio.

3. Open `Strawhats_Report.Rmd` and run the analysis.

4. To view the existing rendered report, open `Strawhats_Report.html` in a web browser.

Install any required packages that are missing, based on the libraries used in the R Markdown document.

## Analysis Areas

- **Saga Progression:** Explore how episodes are organized across the series.
- **Episode Distribution:** Analyze the distribution of episodes among sagas and story arcs.
- **Story Arc Duration:** Compare story arc lengths and identify duration trends.
- **Data Preparation:** Convert API-sourced JSON data into structured, analysis-ready formats.
