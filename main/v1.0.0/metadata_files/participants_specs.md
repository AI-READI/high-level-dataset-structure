# participants.json and participants.tsv

## About
The participants.json and participants.tsv files are metadata files containing basic information about the participants in the study. 
The participant.tsv file contains the information while the participant.json file acts as a sidecar that describes the columns in the participant.json file.
These files are replicated from from the [Brain Imaging Data Structure (BIDS)](https://bids-specification.readthedocs.io/).

## Specifications

### Requirement
These metadata files are mandatory for all datasets that contain data collect in-vivo, in-situ, or ex-vivo from human or non-human subjects.

### Name
These metadata files must be named `participants.json` and `participants.tsv`.

### Format
The `participants.json` file must be in JSON format and the `participants.tsv` must be in TSV format.

### Location
These metadata files must be located at the highest-level/root-level of the dataset.

### Content
For the exact specification provided in [BIDS v1.8.0](https://bids-specification.readthedocs.io/en/stable/03-modality-agnostic-files.html#participants-file)
for the structure and content of these metadata files. The following keys must be included with an associated value: 
`participant_id`, `species`, `age`, `sex`, along with `strain` and `strain_rrid` if `species` is different than `homo sapiens`. 
Other keys should be included when relevant.
