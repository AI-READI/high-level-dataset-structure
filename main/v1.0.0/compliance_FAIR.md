# Compliance of the BCDS with relevant FAIR principles

## About
The [Findable, Accessible, Interoperable, Reusable (FAIR) data principles](https://doi.org/10.1038/sdata.2016.18) published in 2016 are the outcome of a large scale international effort for increasing the reuse of research data. 
They provide 15 high-level instructions for optimizing the reuse of research data by humans and machines. They are widely adopted by all fields of research, including biomedical research. 
We explain here how implementing the BCDS enables to comply with the FAIR principles related to dataset structure and metadata files. 

## Compliance assessment 

### F2. Data are described with rich metadata (defined by R1 below) 
Jointly, all the metadata files prescribed in the BCDS include rich metadata necessary for any re-user (human or machine) that is looking at the dataset for the first time.

### F3. Metadata clearly and explicitly include the identifier of the data they describe. 
The identifier of the dataset is included in the dataset_description.json and README.md metadata files, which are mandatory in the BCDS.

### I1. (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation. 
All the metadata files prescribed in the BCDS are in a file format that is typical for such metadata files and their content make use of controlled vocabularies when applicable. Specifically:

- The dataset_description.json is in the JSON format, which is a standard format for a metadata file aimed to be machine readable. The BCDS imposes the content of this metadata file to follow the [DataCite JSON](https://doi.org/10.5438/1pca-1y05) structure with the [DataCite Metadata Schema 4.4](https://doi.org/10.14454/3w3z-sa82), which is a standard schema with controlled vocabulary based on the [DataCite Ontology](https://sparontologies.github.io/datacite/current/datacite.html) that is widely used for documenting research outcomes. The schema is extended in the BCDS with the [ECRIN Metadata Schema v6.0 extension](https://doi.org/10.5281/zenodo.5554961), a schema developed to complement the DataCite Schema with terms related to clinical studies.   

- The README.md is in the markdown format, which is standard format for a metadata file that is aimed at providing an onverview of a research object (dataset, software, etc.) in a human-friendly format. There are no known standards for the structure and content of such a metadata file. Given the variety of datasets and personal preferences, the BCDS is not imposing any either. The BCDS, however, does impose specific information to be included in this file such that the content deemed necessary for dataset reuse in consistent across datasets. 

- The participants.tsv and participants.json are replicated exactly from  the [Brain Imaging Data Structure (BIDS) v1.8.0](https://bids-specification.readthedocs.io/en/v1.8.0/03-modality-agnostic-files.html#participants-file), a widely used structure for neuroimaging data. The BIDS imposes a standard structure and the use of controlled vocabulary in these files which is mimicked in the BCDS.

- The CHANGELOG.md in the markdown format, which is standard format for such a metadata file that documents changes between different versions of a research object (dataset, software, etc.). The BCDS imposes the content of this metadata file to be structured following the [Keep a changelog v1.1.0](https://keepachangelog.com/en/1.1.0/) conventions. Instructions are also provided in the BCDS for using standard format for certain content of this metadata file, such as [Semantic Versioning 2.0.0](https://semver.org/) for the version number of the dataset, [ISO-8601 format](https://en.wikipedia.org/wiki/ISO_8601) for the release date, and specific categories to organize the release notes for each verison.

- The LICENSE.txt in the text format, which is standard format for such a metadata file that document license terms for a research object (dataset, software, etc.). The BCDS imposes, when possible, to use a standard license from the [Software Package Data Exchange (SPDX) License List](https://spdx.org/licenses/). which is aimed at developing and promoting open standards for licenses. When using a standard license listed in the SPDX license list, the BCDS also imposes the content of this file to be exactly as the text listed in the "Text" section of that license on the corresponding SPDX page, which are the official standard terms of that license. 

- The samples.tsv and samples.json are replicated exactly from  the [Brain Imaging Data Structure (BIDS) v1.8.0](https://bids-specification.readthedocs.io/en/v1.8.0/03-modality-agnostic-files.html#samples-file), a widely used structure for neuroimaging data. The BIDS imposes a standard structure and the use of controlled vocabulary in these files which is mimicked in the BCDS.

### I2. (Meta)data use vocabularies that follow the FAIR principles 

### I3. (Meta)data include qualified references to other (meta)data 

### R1. (Meta)data are richly described with a plurality of accurate and relevant attributes 

### R1.1. (Meta)data are released with a clear and accessible data usage license 

### R1.2. (Meta)data are associated with detailed provenance 

### R1.3. (Meta)data meet domain-relevant community standards
