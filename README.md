![ELViS LOGO](elvis-logo.png)

*European Loans and Visits System* 

This repository is part of [DiSSCo](https://dissco.eu) (Distributed System of Scientific Collections), a 
new world-class Research Infrastructure (RI) for natural science collections. ELViS will be a one-stop shop for researchers to provide access to specimens (visits, loans, digitisation on demand) in natural science collections in Europe. 

ELViS is a deliverable of the [SYNTHESYS+](http://www.synthesys.info/) project, and will initially provide open access 
to over 490 million specimens at 21 institutions in Europe through the SYNTHESYS+ Transnational Access (TA) and Virtual 
Access (VA / Digitisation on Demand) programmes. It will replace the SYNTHESYS portal for TA applications. 

Currently, ELViS is being developed in three stages: 

- A system for Virtual Access, to support the first VA call in February 2020 (Milestone 50)
- The first version of ELViS to be used for the second VA call and third TA call in January 2021 (Milestone 51)
- A second version of ELViS for early 2022 including an integrated collections dashboard (NA2 output) and Authorisation and 
Authentication (AAI) pilot.

ELViS uses DiSSCo architecture design as its foundation as it will pilot some of the design choices 
for the DiSSCo infrastructure. After the SYNTHESYS+ project, the ELViS system will become a core part of the 
DiSSCo e-services. It will be further developed and maintained in the DiSSCo Prepare and Construction phases. 
It will scale up after SYNTHESYS+ to provide access to approx. 1.5 Billion specimen in the 100+ DiSSCo collection holdings. 
The DiSSCo architecture is being designed in the [ICEDIG](https://www.icedig.eu/) project and described in the Specimens 
Digital Objects Architecture (DSArch) and the provisional DiSSCo [Data Management Plan](http://doi.org/10.5281/zenodo.3532937) 
(DMP), deliverable 6.6 in the ICEDIG project. 
The DiSSCo architecture design is based on FAIR [Digital Objects](https://www.dona.net/digitalobjectarchitecture) 
(FAIR DO) and the Digital Object Interface Protocol Specification (DOIPv2).

## Components 
ELViS will have the following components:

- Registration for Virtual Access (VA)
  - Digitisation on Demand (DoD) transactions
- Registration for Transnational Access (TA)
 - Loans transactions
 - Visits transactions
- Peer review transactions 
- Interactive Dashboard view
- Reporting views
- Helpdesk
- Profiles 
  - Individuals
  - Collections
  - Institutions
- Authentication and Authorisation Infrastructure (AAI)

## Data Sources 

<p align="center">
  <img align=center src="elvis-data-sources.png" alt="ELViS data sources"></img>
</p>



Some of the data sources currently considered for ELViS 
(the data flow, integration details are still under discussion): 

- CETAF Passports
- CETAF Collection registry
- GrSciCol
- GRID
- ORCID
- GBIF+CoL
- GeoCase
- Index Herbariorum
- WikiData
- GGBN
- DataCite
- Synthesys portal


