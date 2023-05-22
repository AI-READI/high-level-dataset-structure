# CHANGELOG.md

## About
The CHANGELOG.md is a metadata file containing information about the changes between different versions of the dataset that are released. 
This file is intended to provide a human and machine readable overview of different versions of the dataset that are released, their release date, 
and changes included between the different versions. It is inspired by the CHANGES.txt metadata file found in the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/) 
and the [SPARC Data Standards (SDS)](https://docs.sparc.science/docs/overview-of-sparc-dataset-format).

## Specifications

### Requirement
This metadata is mandatory for all datasets, even for the first release.

### Name
This metadata file must be named `CHANGELOG`.

### Format
This metadata file must be in the markdown format. The full name with extension must thus be `CHANGELOG.md`.

### Location
This metadata file must be at the highest-level/root-level of the dataset.

### Content
The content must be structured following the [Keep a changelog v1.1.0](https://keepachangelog.com/en/1.1.0/) conventions and must include the specified information, i.e.:
- The content of the file must start with a “Changelog” title.
- The preamble must explain what this changelog file is for and specify the format followed (i.e., Keep a changelog v1.1.0 and Semantic Versioning 2.0.0). 
- There must be an entry for every single version.
- The latest version must be listed first.
- Each release note  must start with a version number as a title followed by the release date. 
The version number must follow the [Semantic Versioning 2.0.0](https://semver.org/) and the release date must follow the [ISO-8601 format](https://en.wikipedia.org/wiki/ISO_8601) (YYYY-MM-DD). 
- The content of each release note must be organized under these categorises as applicable (the definition of the categories have been adapted 
from Keep a changelog conventions to be more suitable for datasets):
  - “Added”:  High-level explanation of the new data or metadata files that have been added.
  - “Changed”: High-level explanation of previously published data or metadata files that have been modified.
  - “Removed”: High-level explanation of the previously published data or metadata files that have been removed.
