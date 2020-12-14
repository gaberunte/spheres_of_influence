# spheres_of_influence
This repository holds the data, analyses, and figure development for our "Spheres of Influence" manuscript. The project focuses on questioning the drivers of soil fungal community turnover in a mixed hardwood-conifer forest. The study was conducted at Sedgwick Reserve in Southern CA, USA.

**Authors:**
Gabe Runte
Alex Smith
Dr. Holly Moeller
Dr. Laura Bogar

## Structure
Data and code are organized within a single R project (.Rproj). Two .Rmd files (bioinformatics_dada_sedgwick.Rmd and otu_cluster_sedgwick.Rmd) take raw sequence data (not in repo) through filtering and OTU clustering. The other two .Rmd files (otu_to_stats.Rmd and figures_sedgwick.Rmd) are the analyses and resulting figures of the fungal communities. figures_sedgwick.Rmd runs off of a .RData (otu_data_sedgwick.RData) file outputted at the end of otu_to_stats.Rmd and can be run independently. 

Figures are in their own folder at the location outputted from the file paths in the figures_sedgwick.Rmd file. 

## Contact
Please get ahold of Gabe Runte with questions or to access sequence data. This will be accessible through NCBI and we will update this repository with accession numbers. 

Email: gabe.runte@lifesci.ucsb.edu
