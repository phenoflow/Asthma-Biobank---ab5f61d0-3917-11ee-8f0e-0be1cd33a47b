# Asthma-Biobank

Asthma Biobank - PH784

## Requirements

[Docker](https://docs.docker.com/install/) and [CWLTool](https://github.com/common-workflow-language/cwltool#install)

## Configuration

Specify data source credentials in [js/read-potential-cases-fhir.js](js/read-potential-cases-fhir.js).

## Usage

Run: `cwltool Asthma-Biobank.cwl Asthma-Biobank-inputs.yml`

***

### Based on original definition developed by Luke Daines, Ann Morgan, Mome Mukherjee, Mohammad Al Sallakh, Eimear O'Rourke, Jennifer K Quint
### Generated by [Phenoflow](https://kclhi.org/phenoflow).
