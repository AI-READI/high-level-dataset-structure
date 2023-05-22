# dataset_description.json

## About
The dataset_description.json is a metadata file containing provenance metadata, contextual metadata, 
as well as additional metadata necessary for reuse of the dataset. This metadata file is intended to prioritize machine readability. 
It is inspired by the dataset_description metadata file from the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/)
and the [SPARC Data Standards (SDS)](https://docs.sparc.science/docs/overview-of-sparc-dataset-format).

## Specifications

### Requirement
This metadata is mandatory for all datasets.

### Name
This metadata file must be named `dataset_description`.

### Format
This metadata file must be in the json format. The full name with extension must thus be `dataset_description.json`.

### Location
This metadata file must be at the highest-level/root-level of the dataset.

### Content
This metadata file must be structured as per the [DataCite JSON specifications](https://doi.org/10.5438/1pca-1y05). 
The keys in this json file and their values must follow the [DataCite Metadata Schema 4.4](https://doi.org/10.14454/3w3z-sa82) with the 
[ECRIN Metadata Schema v6.0 extension](https://doi.org/10.5281/zenodo.5554961) (indicated with a * in the table below). 
All the keys listed in the table below and their subkeys be included with an associated value when available. 

|       Keys                                                                                
|:----------------------------------------------------------------------------------------:
| `Identifier`                                                                            
| `Creator`                                                      
| `Title`                                                    
| `Publisher`                                                      
| `PublicationYear`
| `ResourceType` (with `resourceTypeGeneral` set to `Dataset` being mandatory)
| `Subject`
| `Contributor`
| `Date` (with `dateType` set to `Created` being mandatory)
| `Language`
| `RelatedIdentifier`
| `Size`
| `Version`
| `Rights`
| `Description`
| `FundingReference`
| `StudyTitle`*
