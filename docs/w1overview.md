# HRR WP1 Functional Overview

**Table of Contents** 

- [HRR WP1 Functional Overview](#hrrwp1functionaloverview)
  - [Overview](#overview)
  - [Target End User](#target-end-user)
  - [Locations](#locations)
  - [Deliverables](#deliverables)
  

## Overview

| End user  | Goal  | Location | # |
| :------------ | :--------------- | :----- | ----:|
| NIPH Metadata Manager | Create variable & data quality documentation | Metadata Management | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries) |
| External Metadata Manager | Create variable & data quality documentation | ?, Internal Integration, Service | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries) |
| Researcher | Read variable & data quality documentation | Tech Info System, Metadata Repository | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries)  |
| EUTRO | Retrieve variable documentation | Metadata Repository, Tech Info System | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries)  |
| Researcher | Access register metadata | Metadata Repository, EUTRO, Tech Info System | [3](#3-registry-metadata-available-to-researchers)  |
| EUTRO | Access NIPH Metadata online | Metadata Repository | [3](#3-registry-metadata-available-to-researchers)  |
| NIPH Data Delivery | Adhere to Data Security & Linkage protocols | DIP(?), FHI Internal | [7](#7-data-security-protocols-for-niph-registries), [8](#8-data-registry-linkage-protocols)  |
| External Data Delivery | Adhere to Data Security & Linkage protocols | ?, Internal Integration | [7](#7-data-security-protocols-for-niph-registries), [8](#8-data-registry-linkage-protocols)  |
| NIPH Data Delivery | Link register data | FHI Internal, Internal Integration, Service | [8](#8-data-registry-linkage-protocols) |
| External Data Delivery | Link register data | FHI Internal, Internal Integration, Service | [8](#8-data-registry-linkage-protocols)  |
| Researcher | Order research file online | EUTRO (?), fhi.no, Registries, Tech Info System | [5](#5-online-research-file-ordering-system)  |
| NIPH Data Delivery | Process online file order | DIP(?), FHI Internal | [5](#5-online-research-file-ordering-system)  |
| Researcher with Data | Analyze data remotely through secure connection | TSD, RAIRD, Private Clouds | [4](#4-secure-remote-logon),  [5](#5-online-research-file-ordering-system)  |
| Researcher with Data  | Access harmonized coding systems | Tech Info System, Tools & Methodology Repo | [2](#2-code-harmonization-icd6-10-and-registry)  |
| Archive (Norstore, NSD, EUTRO) | Adhere to Data Security protocols | Input formats & Data | [7](#7-data-security-protocols-for-niph-registries)  |
| Clinician | Carry out validation study | Service (?) | [10](#10-common-protocols-for-validation-studies)  |


## Target End User

#### Researcher

Any qualified researcher satisfying the requirements to handle register data.  They will be able to:

  - Access and read registry metadata online
  - Access and read data quality reports online
  - Order access to research files online
    - from multiple registries
  - Track the status of their data application


#### Researcher with Data

After recieving data via HRR infrastructure, a researcher with data will be able to:

  - Securely log on to a remote site with access to the data
    - in TSD, RAIRD, Tromsø (?), or private cloud
  - Analyze that data online using tooling available in their project area
    - using research portals and toolchains ecosystems like Galaxy
    - using tools shared through tooling repository
    - with methodology suport from the methodology repository
  - Archive their data set for reproduction and verification
    - with individual identifiers stripped and/or 'managed' for long-term storage

#### NIPH Data Delivery

#### NIPH Metadata Manager

#### External Metadata Manager

#### External Data Dlivery

#### EUTRO

#### Archive

#### Clinician



## Locations


#### Metadata Management

A system for the registration and curation of variable documentation and data quality.

This system may come in whole or in part from the DIP project, from recent investments in comprable systems (SSB, for example), through custom built integrations into register systems.  Barring that, direct injestion of register documentation 

#### Technical Information System

A user friendly system for register researchers tying together resources from the HRR work packages.



#### Metadata repository

An online repository holding structural, content, dataset, and variable metadata for the registers.  Avaiable for use by all partners and in multiple, complementary, formats.

#### Tools and methodology repository

An online resource sharing point for specific tools and methodological knowledge sharing to improve the user experience of working with register data and foster the surrounding research community. 

#### Integration

An integration with pre-existing systems inside the users environment.  This may involve installation and maintenance of custom software, but should integrate well into pre-existing routines and not require "yet another" site for end users.

#### Service

A webservice, or services, available to technical installations throughout HRR.

#### EUTRO

[EUTRO](https://uit.no/om/enhet/artikkel?p_document_id=329938&p_dimension_id=88111&p_menu=155466) is a research project management system that accounts for security, data, and data management throughout the entire research lifecycle.

#### TSD

[Tjenester for Sensitiv Data](http://www.uio.no/tjenester/it/forskning/sensitiv/) provides computing capacity for sensitive data.

#### Private Cloud

Cloud resources operated by the individual researcher either directly, or through a partner.


## Deliverables


#### #1: Improved data quality and data documentation reports for NIPH registries
#### #2: Code harmonization: ICD6-10 and registry
#### #3: Registry metadata available to researchers
#### #4: Secure remote logon
#### #5: Online research file ordering system
#### #6: Online data analysis for researchers pilot
#### #7: Data security protocols for NIPH registries
#### #8: Data registry linkage protocols
#### #9: Expand data quality and data documentation to all central registries
#### #10: Common protocols for validation studies
