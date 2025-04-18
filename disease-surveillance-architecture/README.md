# Public Health Disease Surveillance Architecture
<img src="VM ARCH.png" width="700">

## Overview
This project presents the design and development of a disease surveillance architecture tailored for public health monitoring of COVID-19. It aims to support early detection, reporting, and response to potential outbreaks by integrating data from various health information systems.

## Objectives
- Design a scalable and modular architecture for disease surveillance.
- Integrate multiple data sources including EHRs, lab systems, and reporting tools.
- Ensure interoperability using health IT standards such as HL7 and FHIR.
- Support real-time data analysis and visualization for public health stakeholders.

## Technologies Used
- HL7/FHIR standards
- HAPI-FHIR server (for FHIR resource management)
- OpenEMR (for Electronic health records)
- MySQL (for data storage)
- Apache (for data integration and routing)
- Docker (for containerized deployment)
- Synthea (for synthetic data generation)
- Google collab (for data analysis)
- Google Looker studio (for data aggregation and visualization)[View COVID dashboard here](https://lookerstudio.google.com/reporting/07ebb341-5645-4a19-8a38-82a20a0ed71b/page/VvdGF)

## Challenges Faced
- Aligning various data standards across systems.
- Ensuring data privacy and security in a multi-source environment. We had put in place custom firewalls to ensure web traffic is filtered properly.
- Balancing real-time performance with data integrity and scalability.

## Outcomes
- Developed a high-level architecture diagram for the system.
- Demonstrated end-to-end data flow from clinical systems to public health dashboards.
- Showcased knowledge of modern health informatics tools and standards.

## Folder Contents
- `VM ARCH.png` – Visual representation of the system design.
- `ALL THE OTHER FILES` – Additional notes, flowcharts, and planning documents. The files summarise the whole architecture development, from creating the virtual machines to data aggregation and visualization.

## Author
*Daniel Akama Nyamweya* – Graduate Student in Data Science at Michigan technological University. 
<br/>
Email: *danyamwe@mtu.edu*

