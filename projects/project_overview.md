---
layout: page
title: Five Test Projects
description: Quick Tour of Five Implementations to test Chat architecture
nav_exclude: false
---
# Potential Project suggestions
- Revision of Center for Smart Infrastructure website to incorporate generative PipeChat dialog, with query interfaces to research projects
    - A. Designed for interaction with general public, regulatory bodies, journalism and reporting sites
    - B. Designed for interaction with specialized engineering and utility groups: EBMUD, California State Water Board, LADWP, Metropolitan, PG&E, SFPUC, NSF
- Build Immersive 3-D visualization of EBMUD and UCB distribution and collection piping systems; 
    - HoloLens;  Apple Vision Pro
    - Extend to visualization of thermal flows, structural strains, energy, water, and air flows in UCB campus structures
- Extend UC Berkeley 3-D Digital Twin models
    - Energy, power, thermal, water, steam, particulate; 
    - Complete ontology for all UCB structures and infrastructure
    - Incorporate Large Language model technology to extend Machine Learning models to real-time data analysis of sensor data
    - Develop disaster response model for UCB campus: earthquake,fire, flood, particulate, pathogen, radiation, evacuation and traffic
- Create LLM model of existing UCB Sustainability models
    - Develop LLM embeddings to generate STARS reports on all aspects of UCB operations
    - Integrate with Digital Twin project
- Build LLM models of all UCB Civil and Environmental Engineering classes
    - Create generative models from scientific and engineering literature in civil engineering fields
    - Develop workflow for each course, ingesting video of each course with textual, diagramatic, geospatial, and time-series data flow of labs, lectures, and literature
- Develop computational infrastructure to support use of generative models in all coursework
    - Experiment with all open-source implementations to explore least-cost validated implementations
    - Develop cost model to support innovative research proposals
    - Create computational support for LLM and generative research in civil engineering
- Explore new implementations of Distributed Fiber Optic Sensing
    - Explore least-cost photonics chip and board designs for highly cost-reduced interrogation systems
- Build LLM systems for ingestion of EBMUD pipe repair records, to build machine-learning models for each pipe segment failure prediction
    - Use new LLM and vision-inhanced OCR systems to ingest hundreds of thousands of paper maintenance records
    - build deep learning models based on new attribute data for each pipe segment and pressure zone
    - enhance existing sensing systems with new LIDAR, acoustic, seismic, and EMF field data

# Five Actual Implementations to test Generative Chat architecture against data repositories
## 1. Build complete vector DB for CSI [Center for Smart Infrastructure](https://smartinfrastructure.berkeley.edu/) scientific and engineering reports
## 2. Build VDB of STARS PDF guides, then generate complete UCB Sustainability Report for [STARS Sustainability](https://stars.aashe.org/) architecture

## 3.Digital Twin of UC Berkeley campus: build 3D model of all assets

## 4. [Center for Smart Infrastructure](https://smartinfrastructure.berkeley.edu/) create scientific interviews
## 5. East Bay Municipal Utility District Predictive Model for Water Main Breaks
    - build model of all 4,300 miles of distribution pipe system
    - ingest 20,000 paper records of pipe main repairs from historical archive
    - merge with existing relational DB pipe segment records

![Overview of BSC](../assets/images/BSC Open Reference Architecture-2023-07-15.excalidraw.png)
## 1. Center for Smart Infrastructure
- Ingest all CSI documents
    - Project descriptions, NSF grant applications, project reports
    - theses, scientific papers, scientific publications
    - Finite Element models
    - Test data; all pump, hydraulic element manuals, operational manuals
    - Maintenance reports
- Build CSIChat, interacting with CSI materials for general public access
- Build CSIAnalysis, interacting with FEM, test monitoring real-time data
- Conduct video interviews with all staff, CSI members
    - Build workflow to ingest video, extract transcripts, ingest transcripts into CSIResearchChat

## 2. Sustainability and Resilience
### UC Berkeley Office of Sustainability
- [Sustainability Dashboard](https://sustainability.berkeley.edu/engage/energy-dashboards)
- Ingest all STARS document that form foundation of Sustainability Report
    - 63 PDF at 
- Ingest past UCBerkeley reports
- 2021 Report: [The Sustainability Tracking, Assessment & Rating System](https://reports.aashe.org/institutions/university-of-california-berkeley-ca/report/2021-03-04/AC/curriculum/AC-1/)
- 2021 [Water Report](https://reports.aashe.org/institutions/university-of-california-berkeley-ca/report/2021-03-04/OP/water/OP-21/)
- 
### Lawrence Berkeley Lab Office of Sustainability
 - link to office; annual reports
- LBL digital twin projects: 
    - Supercompter center cooling
    - Building efficiency

## 3. UC Berkeley Digital Twin
 - Create complete 3D model of all aspects of UCB physical plant
 - [Description](/InfrastructureChat/projects/UCB-Digital-Twin.md)
### Build on existing UCB datasets
 - Energy, Power, Water, Gas, Steam
### Extend to full operational Chat
- Ingest all architectural plans, drawings, work orders, punchlists
- Ingest all real-time data: energy, temperature, power, water, waste water, thermal flows, gas, steam
- Ingest all operational manuals, maintenance manuals for all campus structures, assets
- Ingest all operational plans: disaster, earthquake, flood, fire, smoke, chemical spill, radiological spill, particulate emission
### Create compelling 3D models of all UCB: Structures, piping, power distribution, Thermal distribution
 - Can use Cesium, and a JavaScript wrapper--Terria-- for Cesium to put all UCB campus data in one place, then create 3D display. See Australian universities as example.
- Digital Twin: geoJason: site in slack; Australian universities built pioneer visualization of digital twins, and GIS systems. Terria.github;
- Holds other mapping engines in a container; Australia's digital twin ecosystem;
    - minute 54;
    - Cesium-based globe; shows Australia; add layers for water pipes, trains,
    - Add all data in one place; then run simulation behind all the data that is georegistered; Terria.js allows you to build, as a wrapper on top of Cesium
- Need example of how this works with ESRI; how to add each kind of data
- Build example with ETH [Sympheny](https://www.sympheny.com/product)
## 4. CSI Interviews
- Conduct interviews with scientific staff
- Build pipeline to ingest visual, audio materials into generative model
## 5. EBMUD Asset Capture
- Build OCR ingestion pipeline to capture 20,000 existing paper records of water main breaks over 100 years
- Integrate new data with exising relational DB records
- Build vector DB of operational data relating to all pipe elements, valves, pumps, tanks, air pressure regulators, meters, elevation zones