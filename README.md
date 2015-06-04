# HRR Work Package One
On this site you can find tools, documents, and issues for the Health Registries for Research (HRR) Work Package one (WP1).


## Resources

Use the [HRR WP1 project Wiki](https://github.com/hrrno/wp1/wiki) for detailed project information and discussions.

The [HRR WP1 Issue Tracker](https://github.com/hrrno/wp1/issues) contains active issues, feature requests, and status for individual tasks.


## WP1 Goals

| Establish a: |
| :------------|
| Network for the exchange and curation of technical documentation across the central health registries |
| Repository for updating and sharing registry documenation |
| User friendly technical information system for register researchers  |


## WP1 Deliverables

| Deliverable  | Resource  | Status |
| :------------ | ---------------:| :-----:|
| 1. Improved data quality and data documentation reports for NIPH registries |  | dev & planning |
| 2. Code harmonization: ICD6-10 and registry | | analysis |
| 3. Registry metadata available to researchers | [web](http://hrrno.github.io/metadata/), [repo](https://github.com/hrrno/metadata/) | dev |
| 4. Secure remote logon  | | analysis |
| 5. Online research file ordering system | | dev |
| 6. Online data analysis for researchers pilot | | analysis |
| 7. Data security protocols for NIPH registries | |  dev |
| 8. Data registry linkage protocols | | analysis |
| 9. Expand data quality and data documentation to all central registries | | planning  |
| 10. Common protocols for validation studies | | planning |


#### 1: Improved data quality and data documentation reports

* Collaborating with mMFR on documentation editing, storage, and retrieval
* Will investigate synergies with DIP (fall 2015)
* Document processing strategies (via templates or controls), and online editing will be favored


#### 2: Code harmonization

* Direct harmonization is not possible
  * Numerous codes map to 10's or hundreds of newer codes
  * Information is lost or gained through cross-walking
* Historic code information is limited
  * Ole-Henrik has provided historic files in PDF - they will require OCR scanning
* A probibalistic approach may be possible...
  * Ole-Henrik has identified a hospital in Norway that operated under an older coding system for several years
  * Through proper selection and population control it should be possible to calculate a probability of any given code mapping to another
  * This may require a dedicated 'project' with qualified personell...


#### 3: Registry MetaData available


* [Norstore](https://www.norstore.no/services/archive) 's metadata format applied to the MFRs definition
* Structural information used to generate [baseline creation scripts](https://github.com/hrrno/metadata/tree/master/registries/mfr/data/structure)
* International standards for metadata publishing identified
  * Dublin core, DIF, Norstore, Metadata repo format, etc
* Project website: http://hrrno.github.io/metadata
* MetaData repository: https://github.com/hrrno/metadata
* Install the repository and its self-contained web server: [install-metadata-webserver.fsx](https://github.com/hrrno/datamunger/blob/develop/Munger/Scripts/install-metadata-webserver.fsx)


#### 4: Secure remote logon

* FEIDE  is a national standard
* OpenID and Shibboleth are mature and in widespread use
* International federated logons are in the goals of the Tryggve project
* Our computing partners will likely dictate our logon selection


#### 5: Online research file ordering system

* An online prototype interface for MFR has been constructed and is undergoing refinement
* Metadata from the registers will be used to generate data access requests
* Tooling will be constructed so to maximize ease of integration in partner projects


#### 6: Online data analysis for researchers pilot

* Multiple open source research portals have achieved maturity in various disciplines
  * These can be curated and pre-pared for researchers to use in various secure computing environments
* TSD supports [Galaxy](https://galaxyproject.org/)
* Focusing on analysis tool integration and platform management should give us a best-of-breed experience while leveraging established ecosystems and toolchains


#### 7: Data security protocols for NIPH registries

* Pseudonymization, as a information security best practice, has been incorporated into the design of the mMFR
* At-rest and in-transit data security will see marginal improvements
* The secure [PIPE](http://academypublisher.com/jsw/vol03/no02/jsw03022332.pdf) model will be used as a data sharing and security model that supports privacy by design
  * Explicitly shared data subsets, multi-party consent, and shared cryptographic key management
  * A threshold scheme will be applied to data-sharing partners for key and data recoverability
  * Support for cross-register re-identification of data under strictly controlled conditions
* Retroactive data operations to protect data post-release are being considered


#### 8: Data registry linkage protocols

* Analysis of the architecture and solutions of industry leaders has been carried out 
* Tooling has been constructed to allow linkage across pseudonymized registers
* A key interface has been defined in mMFR allowing unified identity operations on central regitries
  * pseudonymized identities can be retroavticely applied to pre-existing registries









