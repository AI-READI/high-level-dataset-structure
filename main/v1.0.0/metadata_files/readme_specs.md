# README.md

## About
The README.md file is a metadata file that contains a detailed description of the dataset in a human-friendly format to supplement the study_description.json and dataset_description.json files. 
You can think about it as a detailed abstract for your dataset, i.e. the first thing that a human reuser of the data will read. This metadata file is inspired by README metadata file from the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/) and the [SPARC Data Standards (SDS)](https://docs.sparc.science/docs/overview-of-sparc-dataset-format), which itself is likely inspired by the README file commonly used to describe software.

## Specifications

### Requirement
This metadata is mandatory for all datasets.

### Name
This metadata file must be named `README`.

### Format
This metadata file must be in the markdown format. The full name with extension must thus be `README.md`.

### Location
This metadata file must be located at the highest-level/root-level of the dataset.

### Content
It is suggested to follow the structure provided in the [template](../../../template). Specifically, this file must contain the information listed below when applicable. It is also suggested to use the section titles listed below for consistency.
- Include the name of the dataset at the top of the file
- **Latest version number**: In this section, indicate the latest version number of the published dataset.
- **Publication date**: In this section, indicate the date when the latest version of the dataset was published (i.e., made available outside of the project members openly or through a restricted access).
- **Identifier**: In this section, indicate the DOI or any other identifier of the latest version of the dataset
- **Overview**: In this section, provide a high-level description of the dataset and the associated study, similar to the abstract of a paper
- **Description**: In this section, provide a more detailed description of the dataset. Include the number of study participants and their characteristics 
(refer to the [participants.json file](participants_specs.md) in your dataset for additional information), the data types collected, the overall number of files and total size of the dataset (as available).
- **Dataset access/restrictions**: In this section, how the dataset can be accessed and any conditions/restrictions for accessing it.
- **Data standards**: In this section, indicate the standards followed to structure the dataset, format of the data files, etc. Make sure to include identifiers of the standards when available and/or link to the associated documentation.
- **Resources**: In this section, mention any external resources that was used for collecting/analyzing/processing the data or may be required/useful to reuse the data (e.g. the study website, the documentation website, software used to collected the data, etc.). Make sure to include identifiers and/or links to the resources.
- **License**: In this section, mention the name of the data reuse license (refer to the [LICENSE.txt](license_specs.md) file in your dataset for additional details).
- **How to cite**: In this section, provide instructions on how to cite the dataset if reused (use the [American Psychological Association (APA) style](https://apastyle.apa.org/))
- **Acknowledgement**: In this section, provide acknowledgement to the funding source and other with identifiers and/or links as applicable.

