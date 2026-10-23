
# Pharmacometrics Integrative Works

This repository contains the integrative coursework completed as part of the **Master of Science in Pharmacometrics**. Each integrative work is organised in its own folder and focuses on different aspects of pharmacometrics.

All projects share a single R project, `Git.Rproj`, located at the repository root.

## Repository Structure

```text
.
├── Git.Rproj
├── README.md
├── integrative-one/
│   └── integrative-one-reports/
├── integrative-two/
└── integrative-three/
```

Each integrative work has its own directory containing the relevant reports, data, scripts, figures, and supporting materials.

## Integrative Works

| Folder                                      | Topic                                                  | Status      |
| ------------------------------------------- | ------------------------------------------------------ | ----------- |
| [`integrative-one/`](integrative-one/)     | Phase I IV vs. oral bioavailability study of Tomovicen | Complete    |
| [`integrative-two/`](integrative-two/)     | Integrative Work 2                                     | Not started |
| [`integrative-three/`](integrative-three/) | Integrative Work 3                                     | Not started |

### Integrative Work 1: Tomovicen Bioavailability Study

The first integrative work focuses on a Phase I crossover study comparing intravenous and oral administration of Tomovicen, a novel tamoxifen-like prodrug.

The project covers data preparation and quality control, exploratory analysis, non-compartmental pharmacokinetic analysis, covariate exploration, and structural pharmacokinetic modelling.

The main deliverables are located in `integrative-one/integrative-one-reports/`, including:

- **Interactive report:** `PMX001_dashboard.html`
- **Report source:** `PMX001_dashboard.qmd`
- **Written report:** `PMX001_report_6page.pdf`
- **Written report source:** `PMX001_report_6page.qmd`
- **Data:** Raw and cleaned datasets
- **Figures:** Supporting visualisations

The HTML report can be opened directly in a web browser to explore the analysis and its visualisations.

## Requirements

The software requirements may vary between integrative works. For Integrative Work 1, the main requirements are:

- [R](https://www.r-project.org/) (version 4.5 or later)
- [Quarto](https://quarto.org/)
- Required R packages, as specified in the individual report source files
- A LaTeX distribution for PDF report generation, such as TinyTeX
- MonolixSuite (PKanalix) for the relevant pharmacokinetic analyses

## Getting Started

1. Clone or download the repository.
2. Open `Git.Rproj` in RStudio or Positron.
3. Navigate to the folder of the integrative work you want to explore.
4. Review the available reports, scripts, datasets, and documentation.
5. Install the required software and R packages before reproducing an analysis.

## Reproducing Reports

For Integrative Work 1, open a terminal in the report directory:

```bash
cd integrative-one/integrative-one-reports
```

Render the interactive report:

```bash
quarto render PMX001_dashboard.qmd
```

Render the written PDF report:

```bash
quarto render PMX001_report_6page.qmd --to pdf
```

Report generation requires the relevant dependencies and input files to be available. Some analyses may also depend on software outside R.

## Data and Reproducibility

The repository is organised to keep each integrative work's materials together and facilitate access to the associated analyses and reports.

Raw and processed data are kept separate where applicable. Report source files document the analytical workflow and can be used to reproduce the outputs when the necessary dependencies and data are available.

Please respect any applicable data confidentiality, access restrictions, and academic requirements when using or sharing the materials.

## Authors

**Integrative Work 1:** Renda V., Bouggar S., Frederickx S., Nangosyah T.

---

*This repository is intended for academic and educational purposes as part of the MSc in Pharmacometrics.*
