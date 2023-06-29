# README.md

## About
The README.md file is a metadata file that contains a detailed description of the dataset in a human-friendly format to supplement the study_description.json and dataset_description.json files. 
You can think about it as a detailed abstract for your dataset, i.e. the first thing that a human reuser of the data will read. This metadata file is inspired by the README metadata file from the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/) and the [SPARC Data Standards (SDS)](https://docs.sparc.science/docs/overview-of-sparc-dataset-format), which is likely inspired by the README file commonly used to describe software.

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
Although not mandatory, it is suggested to follow the structure and section titles provided below and included all the listed information when available:
- **Include the name of the dataset at the top of the file**
- **Latest version number**: In this section, indicate the latest version number of the published dataset.
- **Publication date**: In this section, indicate the date when the latest version of the dataset was published (i.e., made available outside of the project members openly or through a restricted access).
- **Identifier**: In this section, indicate the DOI or any other resolvable identifier of the latest version of the dataset
- **Overview of the study**: In this section, provide a high-level description of the study associated with the dataset. Include identifiers of the study as well as links (website, manuscripts, etc.) to find out more about the study, if available.
- **Description of the dataset**: In this section, provide a detailed description of the dataset. Include the number of study participants (refer to the [participants.json file](participants_specs.md) in your dataset for additional information), the data types collected, data deidentification approaches if any, the overall number of files and total size of the dataset (as available).
- **Protocol**: In this section, provide a link to the protocol(s) followed for collecting and preparing the dataset. If a link is not available, provide a description of the protocol here.
- **Dataset access/restrictions**: In this section, explain how the dataset can be accessed and any conditions/restrictions for accessing it.
- **Data standards followed**: In this section, indicate the standards followed to structure the dataset, format the data files, etc. Make sure to include identifiers of the standards when available and/or link to the associated documentation.
- **Resources**: In this section, mention any specific resources (software, documentation, manuscripts, etc.) that are required/useful for using the data. Make sure to include identifiers and/or links to the resources.
- **License**: In this section, mention the name of the data reuse license (refer to the [LICENSE.txt](license_specs.md) file in your dataset for additional details).
- **How to cite**: In this section, provide instructions on how to cite the dataset if reused (use the [American Psychological Association (APA) style](https://apastyle.apa.org/))
- **Contact**: In this section, provide contact information of someone who can be reached out with questions regarding the dataset. You can also  refer to the study_description.json and dataset_description.json metadata files for information about contact person/entity, authors, and contributors of the dataset.
- **Acknowledgement**: In this section, provide acknowledgement to the funding source and other with identifiers and/or links as applicable.

