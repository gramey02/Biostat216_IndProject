# Biostat216_IndProject
Repo for all files relating to my individual project for Biostats 216, Fall 2021.

## Data files
Project was conducted on a directed network of E.coli metabolic reactions stored in an adjacency matrix
   - AdjData_ecoli.xlsx
and an E.coli metabolic network (iJO1366.mat) from the BiGG database which can be found here:
   - http://bigg.ucsd.edu/models/iJO1366

## .mat files
  - Ecoli_FBA.m - Script to run Flux balance analysis (FBA) to determine essential reactions
  - Ecoli_cascadeNums.m - Script to cascade algorithm on each node
  - cascade.m - algorithm to calculate cascade number for a node
  - in_degrees.m - algorithm to calculate in degree for each node

## .py files
   - 

## .Rmd files
   - NewEcoliFig_Stats.Rmd - Markdown file to merge output data, create new figure, and run new statistics (different correlation method and glms)
