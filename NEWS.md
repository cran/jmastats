# jmastats 0.3.0

## New features

* Retrieve climatological normals based on past data using `jma_collect()` (#20).

## Datasets

* Various datasets handled by the package have been updated to the latest version in January 2025.

# jmastats 0.2.2

## Datasets

* Various datasets handled by the package have been updated to the latest version in July 2024.

## Fixes

* The coordinates and prefecture code of the station dataset have been corrected.

# jmastats 0.2.1

## Datasets

* Various datasets handled by the package have been updated to the latest version in March 2024.

# jmastats 0.2.0

* Initial release for CRAN.

## Features

* Added an interval when executing `jma_collect()` for reducing the load on the server.
* A message is displayed when the data obtained by `jma_collect()` contains values such as missing values.

## Fixes

* Fixed an issue with parameters when acquiring data with `jma_collect()`.

## Datasets

* Various datasets handled by the package have been updated to the latest version in March 2023.

# jmastats 0.1.0

* Data is now downloaded and saved in a local folder using rappdir package. 
In acquiring data under the same conditions, locally stored files are loaded.
* Added a `NEWS.md` file to track changes to the package.
