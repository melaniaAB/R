# Drug-like Targets for Coronavirus.
> The study objective: Characterization of the molecules with drug-like properties to control coronavirus.    
Approach: Data analysis and ML on Chembl data.


## Table of contents
* [General info](#general-info)
* [Drug-like molecules](#image)
* [Packages and approaches](#R)
* [Status](#status)
* [Inspiration](#inspiration)


## General info
The characterized drug-like molecules active against coronavirus can contribute to the disease control measures.

## Drug-like molecules
Drug-like molecules, small molecules, can easily enter the cell and affect other molecules in the cell, such as proteins, hence potentially controlling cases like infecton and cancer. .

![Drug-like molecules](./static/Drug_like.png) 
mit.edu

## Packages and approaches
Lipinski's descriptors, ML (Random Forest).


#### Code Example - Lipinski’s Rule application

	sns.boxplot(x = 'class', y = 'NumHAcceptors', data = df_2class)
  
The focus of the rule:
Molecular weight < 500 
Dalton Octanol-water partition coefficient (LogP) < 5 
Hydrogen bond donors < 5 
Hydrogen bond acceptors < 10
  
## Status
Project is ongoing.

## Inspiration
Using bioinfomratics to characterize active small molecules to control infectioous diseases.
