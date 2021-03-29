# Spheres of Influence
This repository holds the data, analyses, and figure development for our "Spheres of Influence" manuscript. The project focuses on questioning the drivers of soil fungal community turnover in a mixed hardwood-conifer forest. The study was conducted at Sedgwick Reserve in Southern CA, USA.

**Authors:**
Gabe Runte,
Alex Smith,
Dr. Holly Moeller,
Dr. Laura Bogar

## Structure
Data and code are organized within a single R project (.Rproj). Two .Rmd files (bioinformatics_dada_sedgwick.Rmd and otu_cluster_sedgwick.Rmd) take raw sequence data (not in repo) through filtering and OTU clustering. The other two .Rmd files (otu_to_stats.Rmd and figures_sedgwick.Rmd) are the analyses and resulting figures of the fungal communities. figures_sedgwick.Rmd runs off of a .RData (otu_data_sedgwick.RData) file outputted at the end of otu_to_stats.Rmd and can be run independently. 

Figures are in their own folder at the location outputted from the file paths in the figures_sedgwick.Rmd file. 

## Data
Project data is all available through the 'data' folder. Within this folder, bioinformatic data can be found within the 'forward' subfolder. To the extent possible, data is left in the formatting in which is was received from labs, sequencing facilities, or packages (e.g. FunGuild) throughout the project with any necessary wrangling done in the available R scripts. 

## Contact
Please get ahold of Gabe Runte with questions or to access sequence data. This will be accessible through NCBI and we will update this repository with accession numbers. 

Email: gabe.runte@lifesci.ucsb.edu
