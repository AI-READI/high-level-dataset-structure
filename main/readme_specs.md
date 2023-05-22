# README.md

## About
The README.md file is a metadata file containing a detailed description of the dataset in a human-friendly format to supplement the dataset_description.json file. 
You can think about it as a detailed abstract for your dataset, i.e. the first thing that a human reuser of the data will read. This metadata file is inspired by an 
homonymous metadata file found in the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/) and the [SPARC Data Standards (SDS)](https://docs.sparc.science/docs/overview-of-sparc-dataset-format), 
which itself is likely inspired by the README file commonly used to describe software.

## Specifications

### Name
This metadata file must be named `README`.

### Format
This metadata file must be in the markdown format. The full name with extension must thus be `README.md`.

### Location
This metadata file must be at the highest-level/root-level of the dataset.

### Content
This file must contain the information listed below. It is suggested to follow the structure provided in the [template](template). 
- Name of the dataset
- Current version of the dataset
- Date the current version was published
- DOI or other identifier of the dataset
- High-level description of the dataset and the associated study
- Detailed description of the dataset. Describe the number of study participants and their characteristics 
(refer to the [participants.json file](participants_specs.md) in your dataset for additional information), the data types collected, the overall number of files and total size of the dataset.
- How the dataset can be accessed and any conditions/restrictions for accessing it.
- The standards followed to structure the dataset, format of the data files, etc. Make sure to include identifiers of the standards 
when available and/or link to the associated documentation.
- Mention to any external resources that was use for collecting/analyzing/processing the data or may be required/useful to reuse the data
(e.g. the study website, the documentation website, software used to collected the data, etc.). Make sure to include identifiers and/or links to the resources.
- Name of the data reuse license and brief description of the terms for reusing the data (refer to the [LICENSE.txt](license_specs.md) file in your dataset for additional details).
- Instructions on how to cite the dataset if reused (in APA format)
- Acknowledgement to the funding source and other as applicable with identifiers and/or links as applicable.

