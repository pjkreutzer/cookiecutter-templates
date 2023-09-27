# Repo for {{project_name}}

## Authors

{{cookiecutter.author}}, {{cookiecutter.contact}}

# Abstract

> {{cookiecutter.abstract}}

# Repo of {{cookiecutter.project_name}}

{{cookiecutter.repo_description}}


## Usage

Short example of how to use this repository, for example to reproduce the paper using a MAKEFILE:

```
make full_paper
```
## Contribution

When contributing please make sure to place your analysis in the `analysis` folder.
Any raw data should go in to `data/raw` and is treated as read only.
Intermediate and clean data are output to `data/modified`
Results are output to the `results` folder.

### File Naming

This project uses the following naming convention for files:

Data and other non-hierarchical files are sorted by date:

`YYYYMMDD-descriptive_name.filetype`

Hierarchical data are index with a leading 0 and start at 01:

`01-exploratory_notebook.ipynb`

`Fig01-scatterplot_content.png`
