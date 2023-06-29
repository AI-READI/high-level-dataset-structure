# study_description.json

## About
The study_description.json is a metadata file that contains provenance metadata, contextual metadata, 
as well as additional metadata about the study associated with the dataset. This metadata file is intended to prioritize machine readability. 

## Specifications

### Requirement
This metadata is mandatory for all datasets.

### Name
This metadata file must be named `study_description`.

### Format
This metadata file must be in the JSON format. The full name with extension must thus be `study_description.json`.

### Location
This metadata file must be located at the highest-level/root-level of the dataset.

### Content
This metadata file must be structured as per the schema provided [here](../schemas/study_description.schema.json). The schema is based on the [ClinicalTrials.gov study structure JSON schema](https://classic.clinicaltrials.gov/api/gui/ref/study_structure) with some of the [ECRIN Metadata Schema v6.0 extension](https://doi.org/10.5281/zenodo.5554961) and along with some customizations that were deemed required for the BCDS.
