# DataSciClubCUMC
Author: Katherine Shakman
Description: My projects related to the CUMC Data Science Club.  

Project proposals for the Hackathon (Dec 2 2017): 

## Project 1: For a pair of neurons a and b, determine whether activating neuron a will increase the correlation between the activity patterns of the two neurons a and b.  
  * Language: Python 3. 
  * Data: My own. 
  1. For a pair of example traces, calculate their correlation coefficient (use of Spearman coefficient seems appropriate for       my data per: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3576830/).  
    * Load the traces (saved as .mat files) into python.  (See http://www.blogforbrains.com/blog/2014/9/6/loading-matlab-mat-       data-in-python)
  2. For n pairs of traces with condition 1 (no activation of a) and m pairs of traces with condition 2 (activation of a),          find the cross-correlations between each pair and compare correlations in condition 1 with correlations in condition 2        (e.g. are the corrleations higher in one condition than the other?)
    * Calculate the correlation between each pair of recordings.   
  3. Get summary statistics and visualize. 
    * Get the median, mean and SD of the correlation in condition 1 and in condition 2.  
    * Plot the distributions of correlations. 

## Project 2: 
