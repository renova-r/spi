# spi 1.1.9001

Renova release, based on CRAN spi 1.1 (archived on CRAN 2021-02-15).

- `NAMESPACE`: six `importFrom()` directives added: `grDevices::colorRampPalette`, `graphics::axis`, `graphics::filled.contour`, `stats::ecdf`, `stats::qnorm`, `utils::read.table`.
- `man/spi.Rd`: template placeholder `\note` and `\seealso` sections removed (documentation only).
- `DESCRIPTION`: `Title` in title case (`Compute SPI Index`); `Description` spells out the Standardized Precipitation Index (metadata only).
- `DESCRIPTION`: `Authors@R` added and `Author` rewritten as `Josemir Neves [aut, cre]` (metadata only).
- `DESCRIPTION`: stale optional `Date` field removed (metadata only).

Release preparation:

- `DESCRIPTION`: `Version` set to `1.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 2 text) was added; the `License` field is unchanged.
- `README.md` was added and is excluded from the R build.
- `NEWS.md` was added and is excluded from the R build.
