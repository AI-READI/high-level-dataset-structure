# Biomedical and Clinical Dataset Structure (BCDS) v 1.0.0

## Definitions

- The keywords "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC2119](https://www.ietf.org/rfc/rfc2119.txt).
- Dataset: A set of data files issued from a biomedical and/or clinical research project along with associated metadata files.
- Data type: Any type of data file or group of data files that can be collected and interpreted independently of others.

## Data structure
- The data files must be organized into one folder per data type. No data files must be present at the highest level of a dataset. 
- Each folder must be named using the following syntax convention: only a-z characters are allowed (lowercase English alphabet) with the exception of underscores that must be used to separate words (no white space allowed)
- The name of each folder must be derived from the list provided [here](folder_naming.md). 
- Inside each folder, the data must be organized according to existing community-accepted standard for that data type if available or following some other standard structure. This must be documented in the metadata files as required in the metadata files specifications. 

## Metadata files
The following metadata files must be included at the highest level:
- dataset_description.json: A metadata file containing provenance metadata, contextual metadata, as well as additional metadata necessary for reuse of the dataset. This metadata file is intended to prioritize machine readability. See [here](dataset_description.md) for specifications about this metadata file. 
- README.md: A metadata file containing a detailed description of the dataset in a human-friendly format to supplement the dataset_description.json file. See [here](dataset_description.md) for specifications about this metadata file. 
- participants.tsv and participants.json: Metadata files containing basic information about the participants in the study. The participant.tsv will contain the information while the participant.json will act as a sidecar that describes the columns in the participant.json file. See [here](participants.md) for specifications about this metadata file. 
- CHANGELOG.md: A metadata file containing information about the changes between different versions of the dataset that are released. See [here](changelog_specs.md) for specifications about this metadata file. 
- LICENSE.txt: A metadata file containing the terms under which the dataset is shared. See [here](license_specs.md) for specifications about this metadata file. 

## Example

Add image

Point to template
