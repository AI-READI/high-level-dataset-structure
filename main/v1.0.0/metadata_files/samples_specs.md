# samples.json and samples.tsv

## About
The samples.json and samples.tsv files are metadata files that contain basic information about the samples used in the study. 
The samples.tsv file contains the information while the samples.json file acts as a sidecar that describes the columns in the samples.tsv file.
These files are replicated from from the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/).

## Specifications

### Requirement
These metadata files are mandatory for all datasets that contain data collect from samples (e.g., cells and tissues). 
The participants from which those samples are collected must be documented in the [participants metadata files](participants_specs.md).

### Name
These metadata files must be named `samples.json` and `samples.tsv`.

### Format
The `samples.json` file must be in JSON format and the `samples.tsv` must be in TSV format.

### Location
These metadata files must be located at the highest-level/root-level of the dataset.

### Content
Follow the exact specification provided in [BIDS v1.8.0](https://bids-specification.readthedocs.io/en/v1.8.0/03-modality-agnostic-files.html#samples-file)
for the structure and content of these metadata files. The following keys must be included with an associated value: 
`sample_id`, `participant_id`, and `sample_type`. Additional keys could be included when deemed necessary for the reuse of the dataset.
