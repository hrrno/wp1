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
| [NIPH Metadata Manager](#niph-metadata-manager) | Create variable & data quality documentation | [Metadata Management](#metadata-management) | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries) |
| [External Metadata Manager](#external-metadata-manager) | Create variable & data quality documentation | ?, [Internal Integration](#internal-integration), [Service](#service) | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries) |
| [Researcher](#researcher) | Read variable & data quality documentation | [Tech Info System](#technical-information-system), [Metadata Repository](#metadata-repository) | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries)  |
| [EUTRO](#eutro) | Retrieve variable documentation | [Metadata Repository](#metadata-repository), [Tech Info System](#technical-information-system) | [1](#1-improved-data-quality-and-data-documentation-reports-for-niph-registries)  |
| [Researcher](#researcher) | Access register metadata | [Metadata Repository](#metadata-repository), [EUTRO](#eutro-1), [Tech Info System](#technical-information-system) | [3](#3-registry-metadata-available-to-researchers)  |
| [EUTRO](#eutro) | Access NIPH Metadata online | [Metadata Repository](#metadata-repository) | [3](#3-registry-metadata-available-to-researchers)  |
| [NIPH Data Delivery](#niph-data-delivery) | Adhere to Data Security & Linkage protocols | [DIP](#dip)(?), [FHI Internal](#fhi-internal) | [7](#7-data-security-protocols-for-niph-registries), [8](#8-data-registry-linkage-protocols)  |
| [External Data Delivery](#external-data-delivery) | Adhere to Data Security & Linkage protocols | ?, [Internal Integration](#internal-integration) | [7](#7-data-security-protocols-for-niph-registries), [8](#8-data-registry-linkage-protocols)  |
| [NIPH Data Delivery](#niph-data-delivery) | Link register data | [FHI Internal](#fhi-internal), [Internal Integration](#internal-integration), [Service](#service) | [8](#8-data-registry-linkage-protocols) |
| [External Data Delivery](#external-data-delivery) | Link register data | [FHI Internal](#fhi-internal), [Internal Integration](#internal-integration), [Service](#service) | [8](#8-data-registry-linkage-protocols)  |
| [Researcher](#researcher) | Order research file online | [EUTRO](#eutro-1) (?), fhi.no, Registries, [Tech Info System](#technical-information-system) | [5](#5-online-research-file-ordering-system)  |
| [NIPH Data Delivery](#niph-data-delivery) | Process online file order | [DIP](#dip)(?), [FHI Internal](#fhi-internal) | [5](#5-online-research-file-ordering-system)  |
| [Researcher with Data](#researcher-with-data) | Analyze data remotely through secure connection | [TSD](#tsd), RAIRD, [Private Cloud](#private-cloud) | [4](#4-secure-remote-logon),  [5](#5-online-research-file-ordering-system)  |
| [Researcher with Data](#researcher-with-data)  | Access harmonized coding systems | [Tech Info System](#technical-information-system), [Tools & Methodology Repository](#tools-and-methodology-repository) | [2](#2-code-harmonization-icd6-10-and-registry)  |
| [Archive](#archive) (Norstore, NSD, [EUTRO](#eutro)) | Adhere to Data Security protocols | Input formats & Data | [7](#7-data-security-protocols-for-niph-registries)  |
| [Clinician](#clinician) | Carry out validation study | [Service](#service) (?) | [10](#10-common-protocols-for-validation-studies)  |


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


#### NIPH Metadata Manager

Health registry employee at NIPH responsible for generating, and curating registry metadata. Should be able to:

  - Create documentation on variables
  - Detail the 'data quality' of variables and the registry data collection 
  - Add and remove variables
  - Retrieve historic information on variables
  

#### External Metadata Manager

Health registry employee responsible for generating, and curating registry metadata.  Should be able to:

  - Create documentation on variables
  - Detail the 'data quality' of variables and the registry data collection 
  - Add and remove variables
  - Retrieve historic information on variables
  
#### NIPH Data Delivery

NPIH employee resopnsible for delivering data to researchers and other registers, able to:

  - Approve/reject data access applications
  - Approve/reject access to individual variables in an application
  - Revoke access to variables due to new re-identification techniques
  - Join data access registers without being exposed to identifying information
  - Participate in cumulative linking without being exposed to indentifying information
  - Join pseudonymized data sources to one another without being exposed to indentifying information


#### External Data Delivery

Health registry employee resopnsible for delivering data to researchers and other registers, able to:

  - Approve/reject data access applications
  - Approve/reject access to individual variables in an application
  - Revoke access to variables due to new re-identification techniques
  - Join data access registers without being exposed to identifying information
  - Participate in cumulative linking without being exposed to indentifying information
  - Join pseudonymized data sources to one another without being exposed to indentifying information
  

#### EUTRO

An HRR partner supporting large facets of the research process, they should be able to:

  - Access NIPH metadata online
    - in a system friendly manner
  - Access NIPH data quality documentation online
  - Recieve updates to metadata in a 'frictionless' manner 
  

#### Archive

The long term storage solutions for exported data, needs to be able to:

  - Execute data management plans in line with international standards
  - Recieve pseudonymized data sets with accurate metadata
    - authorship metadata
    - dataset metadata
    - variable documentation 
  - Support post-facto operations to protect privacy in a long-term preservation context
    - Deletion, redaction, unpublishing, and re-anonymization 
    - Share long-term identity preservation with publishers to support digital permenence and strict privacy concerns


#### Clinician

A doctor with direct patient contact involved in research, should be able to:

  - Participate in a validation study 
    - based on common protocols
    - using medical quality registries (?)


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

#### FHI Internal

An internal-facing site/installation available to FHI employees.

#### DIP

Internal FHI project to address the needs of our data delivery operations.

#### Internal Integration

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

Documentation to be created through the [Metadata Management](#metadata-management) system, documentation to be displayed through the [Technical Information System](#technical-information-system)

#### #2: Code harmonization: ICD6-10 and registry

An attempt at code harmonization, avaiable as a seperate service, or individual published work.
The harmonization may become its own research project...

#### #3: Registry metadata available to researchers

Collected and generated metadata will be presented in the [Technical Information System](#technical-information-system), EUTRO, and directly available from the [Metadata Repository](#metadata-repository).

#### #4: Secure remote logon

Logon to a secure facility, through FIEDE.

#### #5: Online research file ordering system

Order access to files from multiple registries.  This service may be hosted on individual regitry sites, a common portal, the [Technical Information System](#technical-information-system), or perhaps integrated with EUTRO or another partner facility.

#### #6: Online data analysis for researchers pilot

Access to a secure computing resources and analysis tools.  Multiple research gateways could be relevant, tools and data from HRR should be available inside them.

#### #7: Data security protocols for NIPH registries

Protocols governing the data security for the NIPH registries on the HRR infrastructure.  Best-of-breed solutions require pure pseudonymized operations and consistent data operations.  Information security, PIPE, and our concession framework will cooperate to ensure provable data security. 

#### #8: Data registry linkage protocols

Protocols governing the linking of registers.  The concession framework will allow access management across multiple geographic registers.  Pure psuedonymized registers with appropriately detailed metadata, under the PIPE framework, will provide a clear framework for secure asynchronous linking.

#### #9: Expand data quality and data documentation to all central registries

Expand the [Metadata Management](#metadata-management) system, or harvesting of data to the [Metadata Repository](#metadata-repository), so that all central registers can be represented in EUTRO and other repositories.

#### #10: Common protocols for validation studies

Protocols for sharing validation studies across medical quality registers.  Leveraging concession and linking framework, along with PIPE, should provide a simplified mechanism to initiate validation studies.
