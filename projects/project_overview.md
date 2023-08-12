---
layout: page
title: Five Implementation Test Projects
description: Quick Tour of Five Implementations to test Chat architecture
---

# Five Implementations to test Chat architecture
- Initial steps
![Overview of BSC](../assets/images/BSC Open Reference Architecture-2023-07-15.excalidraw.png)
(../assets\/images/)
## Center for Smart Infrastructure
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

## Sustainability and Resilience
### UC Berkeley Office of Sustainability
- [Sustainability Dashboard](https://sustainability.berkeley.edu/engage/energy-dashboards)
- Ingest all STARS document that form foundation of Sustainability Report
    - 63 PDF at 
- Ingest past UCBerkeley reports
- 2021 Report: [The Sustainability Tracking, Assessment & Rating System](https://reports.aashe.org/institutions/university-of-california-berkeley-ca/report/2021-03-04/AC/curriculum/AC-1/)
### Lawrence Berkeley Lab Office of Sustainability
 - link to office; annual reports
- LBL digital twin projects: 
    - Supercompter center cooling
    - Building efficiency

## UC Berkeley Digital Twin
 - Create complete 3D model of all aspects of UCB physical plant
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