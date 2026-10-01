# Data and Phylogenetic Tree for "Bigger and darker: disentangling effects of body size and climate on insect color lightness"

This repository contains the datasets and phylogenetic tree used in the analyses presented in the associated manuscript.

## Repository Contents

### `df_raw.csv`
The complete compiled dataset.
This file contains all species records and associated trait data assembled from primary and secondary sources prior to filtering.

### `df_final.csv`
The final dataset used for statistical analyses.

This file is a subset of `df_raw.csv` and contains only the species and observations retained after data cleaning, filtering, and validation procedures described in the manuscript. All reported analyses and figures were generated using this dataset.

### `pruned_tree.nwk`
Phylogenetic tree in Newick format.

This tree has been pruned to include only the species present in `df_final.csv`. Species names in the tree correspond directly to those used in the final analytical dataset and can be imported into phylogenetic software or R packages such as `ape`, `phytools`, and `geiger`.

## Contact

For questions regarding the datasets, analyses, or phylogenetic reconstruction, please contact:

**Shantanu Joshi**  
University of Arkansas  
sj058@uark.edu
``
