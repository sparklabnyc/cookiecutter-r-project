# {{cookiecutter.project_name}}

{{cookiecutter.project_desc}}

Created by {{cookiecutter.author}} (<{{cookiecutter.email}}>)

Started on {{cookiecutter.start_date}}

## Project description

This code is used for the paper Name, Y., Parks, R.M. et al. (202X). Title with hyperlink. _Journal Name_.

Aims:

- Aim 1. File `R/model.R`.

Findings:

- Findings 1. File `analysis/`
- Findings 2. File `reports/`

## Directory structure

```md
.
├── .gitignore
├── README.md
├── renv.lock
├── renv
├── {{cookiecutter.project_slug}}.Rproj
├── data
│   └── subfolder
├── R
│   ├── model.R
│   ├── preprocessing.R
├── output
├── analysis
│   ├── analysis.qmd
└── reports
```

| Folder     | File              | Description                                            |
|------------|-------------------|--------------------------------------------------------|
| `data`     | `population.csv`  | Population data                                        |
|            | `shapefile.json`  | Shapefile                                              |
| `R`        | `preprocessing.R` | Data preprocessing steps                               |
|            | `model.R`         | Model                                                  |
| `output`   | `processed.csv`   | Modelled data                                          |
| `analysis` | `analysis.qmd`    | Main data analysis for finding X                       |
| `reports`  | `paper.docx`      | Final paper                                            |

## Running the code

We use [`renv`](https://rstudio.github.io/renv/articles/renv.html) for package dependency management and reproducibility.
You will need to run `install.packages('renv')` in your base `R` distribution.

To get the same packages as we used, run `renv::restore()` and then run the scripts.

## Data availability

Data used in the analysis are controlled by the XX who do not have permission to release data to third parties.
Individual mortality data can be requested through XX (e.g. the US CDC).
If you would like a file containing simulated data that allow you to test the code, please contact <{{cookiecutter.email}}>.
