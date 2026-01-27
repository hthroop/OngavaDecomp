# OngavaDecomp

This project contains shared documentation and code for the June 2024 - October 2025 decomposition project at Ongava Research Centre. 

All data for this project are stored in the ASU DERT Dropbox. Data are pulled into R using a user-specific config file that maps to the Dropbox folder on their machine. Most code in this repo are structured to run from within this repo, reading data from the DERT Dropbox and writing summary data files, figures, analysis results, and other output to Dropbox.

Note that each user will need a copy of the file "config.yml" in their local copy of this repo. The config.yml file will direct R to the correct Dropbox path to read and save files in Dropbox. For more information on this, please see the file "DERT Data and Code Storage" in our Dropbox (DERT/Field and Lab SOPs/Data SOPs).

Note that some of the earlier code is currently not structured to pull and write to Dropbox. This is being updated. 

The project is structured with the following folders:

code: source code (.qmd) for analyses in R. 
OngavaPPT_WorldClim_files: code and analyses for climate data that were used for determining the watering treatments
figs: these are climate data output files that have not yet been moved to be written directly to Dropbox. ** this folder is slated for removal **
output: these are analyses that have not yet been moved to be written directly to Dropbox. ** this folder is slated for removal **

Contact Information
Heather Throop: heather.throop@asu.edu
