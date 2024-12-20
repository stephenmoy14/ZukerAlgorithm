# RNA Secondary Structure Prediction Using Zuker's Algorithm
This repository contains the implementation of RNA secondary structure prediction based on Zuker's algorithm, utilizing Turner parameters for energy calculations. The project includes a Jupyter Notebook for model execution, along with files for Turner parameters and test sequences used for validation.

# Contents
CS466_Final_Project.ipynb: A Jupyter Notebook that implements Zuker's RNA secondary structure prediction algorithm using Turner parameters for energy calculations.
rna_turner2004.par: File from ViennaRNA 2.0 package containing the Turner parameters used for energy calculations in the RNA secondary structure prediction.
rnafold.small.rna_turner1999.par.mfe.gold: A text file from ViennaRNA 2.0 package containing sequences used for testing the algorithm's performance. Each sequence is accompanied by the reference secondary structure and the minimum free energy (MFE) value.

# Installation
To run this project, download the ipynb file and open in Google Colab. Upload the files from ViennaRNA package into the content folder and run the cells.

# Acknowledgments
The Turner parameters used in this project are based on the work by Turner and colleagues, widely recognized for their contributions to RNA secondary structure prediction.

The Zuker algorithm is a well-known approach for RNA secondary structure prediction based on dynamic programming.

The ViennaRNA package is a widely used tool to predict RNA secondary structure.
