# Code to accompany Inferring trees with IQTREE lecture

# Acknowledgments

These scripts and content were borrowed and adapted from 
- The Gene Tree species tree tutorial by Bui Minh <http://www.iqtree.org/workshop/molevol2022>.  Please see for more information. 
-  And Rob Lanfearʻs excellent blog post about concordance factors <http://www.robertlanfear.com/blog/files/concordance_factors.html> with R code to help with analysis. 
-  See Methods Paper: 
Bui Quang Minh,  Matthew W Hahn,  Robert Lanfear
New Methods to Calculate Concordance Factors for Phylogenomic Datasets 
Molecular Biology and Evolution, Volume 37, Issue 9, September 2020, Pages 2727–2733,
<https://doi.org/10.1093/molbev/msaa106>

A huge mahalo to these authors for their generosity in sharing their knowledge. 	

# Accompanying lecture:

This repository contains code and files to accompany the lecture:
<https://mbutler808.github.io/rclass/posts/2023-04-13-iqtree-phylogenetics/>

# Run the `iqtreerun.sh` shell script

1.  In Terminal (MacOS) or git-bash (Windows), navigate to the TurtleTutorial folder
2.  execute the shell script by typing `./iqtreerun.sh` 
    If that fails try `bash iqtreerun.sh`, or look up the error message
    Read the notes in the shell script
3.  Explore the output in R with the `concordance.R` script
4.  Visualize trees either in R (see script), or with a treeviewer such as FigTree
5.  Refer to the lecture for explanations 

__input__: folder with input files
__out__: folder for IQTREE output (out is created by iqtreerun.sh)