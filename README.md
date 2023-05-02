<h1 align="center">
  <br>
  <a href="https://frbcesab.github.io/good-practices"><img src="https://raw.githubusercontent.com/rdatatoolbox/.github/main/profile/logo-rdatatoolbox_150dpi.png" alt="Logo" width="200"></a>
  <br>Reproducible research<br>
</h1>

<h4 align="center">Good practices
<br>
<a href="https://frbcesab.github.io/good-practices" target="_blank"><b>frbcesab.github.io/good-practices</b></a></h4>

<p align="center">
  <a href="https://quarto.org/">
    <img src="https://img.shields.io/badge/Made%20with-Quarto-blue.svg" alt="Quarto">
  </a>
  <a href="https://choosealicense.com/licenses/mit/">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License MIT">
  </a>
</p>

<p align="center">
  <a href="#content">Content</a> •
  <a href="#contribute">Contribute</a> •
  <a href="#citation">Citation</a> •
  <a href="#code-of-conduct">Code of Conduct</a>
</p>

![](img/screenshot.png)


<br>


## Content

This online presentation, available at [**frbcesab.github.io/good-practices**](https://frbcesab.github.io/good-practices)
provides an introduction to the good practices in reproducible research.


<br>


## Contribute

### System requirement

- [R](https://cran.r-project.org/)
- [RStudio](https://posit.co/download/rstudio-desktop/)
- [Quarto](https://quarto.org/)

### Edit slides

- Clone this repository

```sh
## Using the SSH protocol ----
git clone git@github.com:frbcesab/good-practices.git

## Using the HTTPS protocol ----
git clone https://github.com/frbcesab/good-practices.git
```

- Install required packages

Required R packages are listed in the 
[`DESCRIPTION`](https://github.com/frbcesab/git-for-r-user/blob/main/DESCRIPTION)
file.

```r
## Install 'remotes' package (if necessary) ----
install.packages("remotes")

## Install required packages ----
remotes::install_deps()
```

- Edit the 
[`index.qmd`](https://github.com/frbcesab/good-practices/blob/main/index.Rmd) 
file

### Render HTML presentation

```r
## Render HTML presentation ----
quarto::quarto_render("index.qmd")
```


<br>


## Citation

Please cite this presentation as:

> Casajus N & Coux C (2023) Reproducible research - Good practices. URL: <https://frbcesab.github.io/good-practices>.


<br>


## Code of Conduct

Please note that this project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
