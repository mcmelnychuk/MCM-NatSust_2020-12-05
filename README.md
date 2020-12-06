# MCM-NatSust_2020-12-05
Input data and code for analysis to accompany the manuscript: "Identifying Management Actions that Promote Sustainable Fisheries" by Melnychuk et al., 2020, Nature Sustainability, https://doi.org/10.1038/s41893-020-00668-1.

Copy the file 'MCM-NatSust_2020-12-05.zip' to your preferred directory on your local machine, and unzip file. Within the directory 'MCM-NatSust_2020-12-05', there are two sub-directories:

1. 'MCM-NatSust'

The files and folder structure within the sub-directory 'MCM-NatSust' are part of a R-project. The set of files is most easily run using RStudio. In RStudio, open R-project 'MCM-NatSust' (use File > Open Project, and navigate to sub-directory 'MCM-NatSust' on your local machine). RStudio will now treat this sub-directory as the root directory for the project. Seven script files are contained in this root directory, and input data files are contained in the sub-directory 'in-data'. These script files will input data files, run analyses, and produce data output files and .pdf figure files.

Open file 's1_main.R' for further instructions and to source all scripts for analysis.

If using an alternative to RStudio, set the working directory to the root directory on your local machine: to check: use getwd() to reset: use setwd() and then source file 's1_main.R'.

Necessary packages will be loaded, or if not yet installed, will be installed. One package ("coefplot2") requires Rtools, and must be installed manually. See instructions under 'LOAD PACKAGES' of file 's1_main.R'.

2. 'Figures 1b and S3'

This contains code and input data for generating two other figures. Open file 'figs_1b-S3.R' in R. (Either open this file from its sub-directory in RStudio, or else set the working directory in R to this sub-directory.) Run the script or source the file, which will load data files and generate two .png files.

Version history:

'MCM-NatSust_2020-07-08.zip', code files and README for initial submission

'MCM-NatSust_2020-10-14.zip', code files and README for revised submission

'MCM-NatSust_2020-12-05.zip', code files and README for accepted version
