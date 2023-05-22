# Folder naming guidelines

## About
The BCDS specifies to maintain one folder per data type. There are likely an infinite ways to label a data type and therefore an infinite ways to name each data type folder. 
For instance, data issued from optical coherence tomography imaging can be labeled as "OCT", "oct", "optical coherence tomography", "Optical Coherence Tomography", "oct_imaging", or "OCT data", etc. 
To provide a consistent naming scheme and facilitate data reuse, a data type dictionnary has been established as part of the BCDS and must be used to name the data type folders.

## Specifications
Each high-level folder in the BCDS must be named with one element from the data type dictionnary available [here](data_type_dictionnary.csv). See the "Adding to the dictionnary" section below if a correponding name for your data type is not found. 

## About the data type dictionnary

### Naming process
The following process was followed for each data type documented in the dictionnary:
1. Search the [BioPortal](http://bioportal.bioontology.org/) maintained by the National Center for Biomedical Ontology (NCBO) with terms related to the procedure, tests, and/or devices associated with the data type.
2. Select a standard term for the data type based on the search results:

    2.1. If a standard term is found, retain the standard term from the top most relevant bio-ontology recommended by the NCBO Ontology Recommender 2.0.
    
    2.2. If a standard term is not found, suggest a standard term that is intuitive for uniquely understanding the data type.

3. Format the standard term according to the following convention: only a-z characters are allowed (lowercase English alphabet) with the exception of underscores that must be used to separate words (no white space allowed).

### Adding to the dictionnary
Given the large number of data types in biomedical and clinical research, not all are documented in the data type dictionnary. If your dataset contains a data type not currently documented in the dictionnary,
please create a pull request from the main branch and suggest a new entry in the `data_type_dictionnary.csv` file under the main folder. Make sure to follow the naming process described above and
provide all the details required in the dictionnary.





