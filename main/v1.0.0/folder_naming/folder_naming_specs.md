# Folder naming guidelines

## About
The CDS specifies to maintain one folder per data type. There are likely an infinite ways to label a data type and therefore an infinite ways to name each data type folder. 
For instance, data issued from optical coherence tomography imaging can be labeled as "OCT", "oct", "optical coherence tomography", "Optical Coherence Tomography", "oct_imaging", or "OCT data", etc. 
To provide a consistent naming scheme and facilitate data reuse, a data type dictionary has been established as part of the CDS and must be used to name the data type folders.

## Specifications
Each high-level folder in the CDS must be named with one element from the data type dictionary available [here](data_type_dictionary.csv). See the "Adding to the dictionary" section below if a correponding name for your data type is not found. 

## About the data type dictionary

### Naming process
The following process was followed for each data type documented in the dictionary:
1. Search the [BioPortal](http://bioportal.bioontology.org/) maintained by the National Center for Biomedical Ontology (NCBO) with terms related to the procedure, tests, and/or devices associated with the data type.
2. Select a standard term for the data type based on the search results:

    2.1. If a standard term is found, retain the standard term from the top most relevant bio-ontology recommended by the NCBO Ontology Recommender 2.0. If the term is reused from another ontology, refer to the main ontology.
    
    2.2. If a standard term is not found, suggest a standard term that is intuitive for uniquely understanding the data type.

3. Format the standard term according to the following convention: only a-z characters are allowed (lowercase English alphabet) with the exception of underscores that must be used to separate words (no white space allowed).

### Adding to the dictionary
Given the large number of data types in clinical research, not all are documented in the data type dictionary. If your dataset contains a data type not currently documented in the dictionary,
please create a pull request from the main branch and suggest a new entry in the `data_type_dictionary.csv` file under the main folder. Make sure to follow the naming process described above and
provide all the details required in the dictionary.





