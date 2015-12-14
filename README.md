# RTCGA.clinical

A part of [RTCGA](https://github.com/RTCGA) family.

To install development version from GitHub use

````{R}
if (!require(devtools)) {
    install.packages("devtools")
    require(devtools)
}
install_github("RTCGA/RTCGA.clinical", build.vignettes = TRUE)
````

Make sure you have [Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed on your computer, if you are trying `devtools` on Windows.

To install Bioconductor development version use (the same as GitHub development version)

````{R}
BiocInstaller::useDevel() # swiches to devel branchof Bioconductor
source("https://bioconductor.org/biocLite.R") # downloads bioClite function
biocLite("RTCGA.clinical") # installs a package
````

