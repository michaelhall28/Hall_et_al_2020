Notebooks to generate the figures for Hall et al., Biorxiv, 2020

## Software Requirements
-python 3

darwinian_shift code available from https://github.com/michaelhall28/darwinian_shift  
Follow the instructions on that repository to install the code and download the required reference files for GRCh37.


Other python packages required:
- jupyter
- matplotlib
- numpy
- pandas
- seaborn


## Data requirements
To run the notebooks, the following files should be downloaded and placed in the same directory as the notebooks.  

The mutation data used come from Martincorena et al. Somatic mutant clones colonize the human esophagus with age. Science. 2018.  
The data used is in Supplementary Table 2 and can be downloaded from here: https://science.sciencemag.org/highwire/filestream/716966/field_highwire_adjunct_files/2/aau3879_TableS2.xlsx  

To run the Transmembrane_mutations notebook a bigwig file of Phylop conservation scores is required. This file can be downloaded through the UCSC genome browser here: http://hgdownload.soe.ucsc.edu/goldenPath/hg19/phyloP100way/hg19.100way.phyloP100way.bw   
Warning - this file is approximately 9Gb.  
