---
layout: page
title: Five Test Projects
description: Quick Tour of Five Implementations to test Chat architecture
nav_exclude: false
---

# Five Implementations to test Generative Chat architecture against data repositories
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