# Coral multidisease microbiome project

This repository contains all of the code associated with and the analyses performed for: Roitman, S. and Closek, C.J., Pollock, F.J., Jordán-Dahlgren, E., Brandt, M.E., and Medina, M. A comparative microbiome and transcriptome approach for multidisease analysis in Caribbean corals. (in preparation)
#
The Coral_Multidisease_Microbiome_QIIME2_PreProcessing.txt file contains all bash code used to run QIIME2 and process the raw 16S DNA sequences.

INPUT: Raw data are unpublished.

OUTPUT: ASV table, representative sequences file, taxonomy file, and a phylogenetic tree. 

#
The Coral_Multidisease_Microbiome_RMardkown_Procedure.rmd file contains all R code used to conduct statistical analyses and generate figures.

INPUT: ASV (features) table, taxonomy table, mapping file, and a phylogenetic tree.

OUTPUT: PERMANOVA and post-hoc results, PCoA plots, alpha diversity plots, line plots, and differntial abundance plots generated using DESeq2.
