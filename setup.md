# Education data setup

## Grabbing this repository
If you have git set up already, clone this repo. If not: go to [https://github.com/UrbanInstitute/ed-data](https://github.com/UrbanInstitute/ed-data). Click the button that says "Clone or download" and press "Download ZIP" to download all of the latest files for this project. Unzip the file.

## R Setup
To work with IPEDS and other data in this project, you'll need to have some things installed on your computer. The main requirements are R and RStudio. You probably have an old version of R installed - [install the latest version](https://www.r-project.org/).

If you have RStudio already, open it up and go to Help > Check for updates. Update RStudio if needed. If you don't have RStudio installed already, [download RStudio](https://www.rstudio.com/products/rstudio/download3/). You may need an admin password to update/install - if that's the case, contact IT.

## R packages
Once R is installed and working, you'll need to install some packages to work with the data. 
Open RStudio, and run this command:

```R
install.packages(c("dplyr", "tidyr", "stringr", "Hmisc", "openxlsx", "readxl"))
```

## JSON generation setup
If you're generating graph JSONS, you'll need all of the above, plus Python3 installed on your computer. You'll also need the latest version of `jsonlite`

```R
install.packages("jsonlite")
```

NEXT: researcher - [Working with IPEDS data](ipedsdata.md) or developer - [Creating graph jsons](graphcreation.md)

Check out a handy [R cheatsheet for data wrangling](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf) and the [Urban Institute R Users Group](https://github.com/UrbanInstitute/R-Trainings).
