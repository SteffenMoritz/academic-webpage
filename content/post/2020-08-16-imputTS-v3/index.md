---
authors:
- Steffen Moritz

categories:
- imputeTS
- Rstats
- Time Series Imputation

tags:
- imputeTS
- Rstats
- Time Series Imputation

date: "2020-08-16T00:00:00Z"

draft: false
featured: false

image:
  focal_point: ""
  placement: 2
  preview_only: false

projects: []

title: 'imputeTS v3.1 now on CRAN'
summary: A new version of the imputeTS package with great new plots is available on CRAN.

---
The newest version (3.1) of the imputeTS package is now on CRAN. It is a major update with all kinds of improvements and additions. Especially the plotting functions are updated and the new visualizations look great.
([Check out the **gallery** of missing data plots](https://cran.r-project.org/web/packages/imputeTS/vignettes/gallery_visualizations.html))

**Main (visible) new features:**

- Plotting functions are all in ggplot now (way better looking, better adjustable)
 
- Plotting functions got new names (ggplot_na_distribution, ggplot_na_intervals, ggplot_na_gapsize, ggplot_na_imputations)

- Speedup for ggplot_na_gapsize calculation

- Added harmonic and geometric mean as option for na_mean

- Removed bug in na_replace -for NA only vectors

- Improved na.random input check (usable with all NA input now if upper and lower bound paramters are exlicitly set to numeric values)

- Added additional missing data stats to statsNA function (Number of Gaps, Average Gap Size)

- Added the imputeTS Cheat Sheet as Vignette

- Added new vignette 'Gallery Missing Data Visualizations'


