
# cdEthio

<!-- badges: start -->
<!-- badges: end -->

The goal of cdEthio is to convert date from the Ethiopian calendar to the Gregorian. 

## Installation

You can install the development version of cdEthio like so:

``` r
# remotes::install.github("DawitJember/cdEthio")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(cdEthio)
## basic example code
##The package has sample_date data
data(package="cdEthio")
##converting date to Gregorian calendar using the sample_data
davedate(a=sample_date$day, b=sample_date$month, c=sampple_date$year, id=sample_date$id)
##If you want the data for further analysis
dateconverted<-davedate(a=sample_date$day, b=sample_date$month, c=sample_date$year, id=sample_date$id)
##check by entering date, month, year for a single individual
davedate(a=5, b=4, c=2013, id=1)

```

