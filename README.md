# spi

Computes the Standardized Precipitation Index (SPI).

Compatibility updates by Renova.

Version 1.1.9001: `NAMESPACE` imports the grDevices, graphics, stats and utils functions the package calls (`colorRampPalette`, `axis`, `filled.contour`, `ecdf`, `qnorm`, `read.table`), placeholder `\note`/`\seealso` sections are removed from `man/spi.Rd`, and the DESCRIPTION title, Description, `Authors@R` and stale `Date` are updated.

## Install

```r
install.packages("spi", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/spi) for builds and installation. This release is tagged on GitHub as `renova-1.1.9001`:

```r
remotes::install_github("renova-r/spi@renova-1.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

spi is by Josemir Neves; the original CRAN package is at <https://CRAN.R-project.org/package=spi>. License: GPL-2; see [COPYING](COPYING).
