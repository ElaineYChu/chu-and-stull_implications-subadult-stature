# Contents

This repository contains full documentation for the paper:
> Chu, E.Y. & Stull, K.E. (In press). An investigation of the relationship between long bone measurements and stature: Implications for estimating skeletal stature in subadults. International Journal of Legal Medicine

To run the code for this paper locally, please ensure that [R](https://cran.r-project.org/), and optionally [RStudio](https://www.rstudio.com/), are installed on the local system. 

### How to cite
Please cite this compendium as:
> Chu, E.Y. & Stull, K.E. (2024). Compendium of R code for “An investigation of the relationship between long bone measurements and stature: Implications for estimating skeletal stature in subadults”. Accessed *Current Date*

## The data
All data are from the [Subadult Virtual Anthropology Database](https://zenodo.org/communities/svad) (SVAD). Specifically, this project uses portions of data from the [United States](https://zenodo.org/record/5193208#.YmWLkdrMLao), which is also directly provided in the [data folder](data).

## How to use this repository
There are two ways to add this repository to a local system:  

1. If you are using a Mac operating system or have another shell terminal system (such as [Git for Windows](https://gitforwindows.org/)), open your terminal and enter the following commands:
  
  ```console
cd "file/path/to/desired/repository/location"  # set file location 
git clone https://github.com/ElaineYChu/chu-and-stull_implications-subadult-stature  # clone the repository
cd chu-and-stull_implications-subadult-stature  # enter the new directory
ls  # check that there are files in the new directory
```

2. If you do not have or are unfamiliar with terminal command systems, you may also locate and click on the green button in this repository labeled "Code" with a downward arrow and select "Download ZIP." This will download a zipped file to your local system (probably found in your *Downloads* folder). Extract the embedded folder ("subadult_sv_2022-main") and relocate it to your desired folder location. 

**Next, rename the folder to "chu-and-stull_implications-subadult-stature" before proceeding further.**  

Inside the **chu-and-stull_implications-subadult-stature** folder, you should find the following folders and files:  

* [data](data) - A folder containing the original subsetted data from SVAD and subsequent files after data manipulation  
* [results](results) - A folder housing the resulting files from all analyses  
* [documentation](chu-and-stull_implications-subadult-stature_vignette.Rmd) - A RMarkdown file containing all code and analyses to replicate publication results. To view a rendered .HTML version of this file, [click HERE](https://rpubs.com/elainechu/chu-and-stull_implications-subadult-stature)  
* [elaine_theme](elaine_theme.R) - A personalized theme for plots using `ggplot2`  












