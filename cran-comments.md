## Updates since last release

- Replaced `%>%` with native pipe `|>` in examples to fix CRAN check errors
- Added `Depends: R (>= 4.1)` for native pipe support
- Removed `LazyData: true` (no lazy data in package)

## Test environments

* local macOS (aarch64-apple-darwin20), R 4.5.3
* ubuntu-latest (on GitHub Actions), R release and R devel
* windows-latest (on GitHub Actions), R release
* win-builder (devel and release)

## R CMD check results

0 errors | 0 warnings | 0 notes

## revdepcheck results

We checked the only reverse dependency, geofacet, comparing R CMD check results across CRAN and dev versions of this package. There were no issues.
