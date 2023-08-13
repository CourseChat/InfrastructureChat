---
layout: page
title: Session.11-July5-Wed-morn
nav_exclude: true
---

# Watch the video

- **Video**: [How websites work](https://drive.google.com/file/d/1X1q-q0ZjjDUS-bP4f7E2xrCnudpahnQD/view?usp=sharing).    1:10:29
- Transcript: not yet
- References:
- Audio:
- Slides: tbd

Session.11
| 11             | 2023-07-05 Wed morn     

# Every project for this summer session will generate a website.  It will generate other things, but it will generate a website.  We will learn how, now.
### What is a website?
## Topics
### What is an IP address? what is DNS? How do you host a CSI Chatbot? How do you do it safely, and how do you find a way to pay for each query to the CSI website?
### 16:09 What is ICANN? What is whois?

### How to create the CSI website

### How to edit the CSI website using the Chrome 
- CSI Chatbot and CSI website
- How to build a personal websites: making websites from scratch; we will create a website for  everyone today.  Basics: 
	- HTML language; hosting HTML pages, CSS, Javascript; what happens when you enter a web address
	- IP addresses: 
	- Domain names; DNS: domain name server;
	- Web Servers: Apache; nginx; Caddy; Django: python environment to build web site
	- no access to the CSI website; Greek company controls the DNS; Content management system runs the site;
	- build a parallel CSI server; tie it to a retrieval augmentation pipeline; 
	- all we do will result in a web site: digital twin; chatbot; EBMUD pipe main breaks; Sustainability chat; 
	- Subdomains of domains; 
	- imtp.google.com; pop3.google.com; smtp.google.com
### 19:50 How to find the CSI domain name; using whois.domaintools.com- search for the CSI site; 
### 21:02 UC Berkeley is a wpengine, WordPress web site, hosted in Texas
	- Internet Corporation for Assigned names and numbers; DB of names to numbers;
	- smartinfrastructure.berkeley.edu; original : 1985; WPengine: Texas, Austin; WordPress engine; WP engine hosts berkeley
	- Cloudflare; 
### 26:00 Using iframes to embed video on the CSI website--Using the editing facility by Shih--Hung
	- How to embed a youtube video; get the  embed fideo iFrame text; copy and paste; show the Spot video inside of the CSI website using ShiHung's access to the Wordpress editor;
	- Demonstrated changing the CSI website
	- This is how to show a website inside another website: an old tool, but still used, by Youtube, for example
### 30:28 The difference between a web site and a web application 40:08

## Projects
### Set up parallel website for all projects: each project has a separate subdomain
	- Next step : create name for each project; create subdomains for each project Build the CSI website.
		- PipeChat or PipeTwin
		- Digital Twin; Project 4
		- Sustainability
		- ChatBot
		- discussion of "Electron", the container holds the software to build the website;
		- webserver must talk to a database containing the web site
### 29:26 Create new domain for our projects
		- create EX01.csi.berkeley domain, or EX01project.org; or .net; or other Top Level Domain; .tv--Tuvalu, .ly--Libya, .ai - Anguilla; draw.io--Indian Ocean;
		- 37:00
		- fiber optic global networks; 
### 40:20  hurricane-electric; he.net; short domain name means it's old. See all the global fibers on the global network map
		- Select one undersea fiber, note the names of endpoints, find IP numbers for racks at each end. Packets flow.  Show the datacenters at each end; 1U; 19 inches; 42U high;
			- how many 1U units were needed for a certain website size?
		- How to render Finite Element Analysis results as an interactive 3D visualization on the CSI website;  embed it in the website;
		- New set of links that enable each project; 
		- "what happens when you type a url in a search engine?  a typical interview question." the seven OSI layers; necessary to know to fix it when it doesn't work.
### 40:08 The difference between a web site and a web application 
	- how do we integrate our LLL chat?  We need a database.
	- how do I connect my database to my webserver?


### 53:58 How we should display our Digital Twin: Use TerriaJs at GitHub: terria.io
- Can use Cesium, and a JavaScript wrapper--Terria-- for Cesium to put all  UCB campus data in one place, then create 3D display.  See Australian universities as example.
- Digital Twin: Jason: site in slack; Australian universities built pioneer visualization of digital twins, and GIS systems. Terria.github; 
### NSW Digital Twin: 55:18. nsw.digitaltwin.terria.io
		- Holds other mapping engines in a container; Australia's digital twin ecosystem; 
		- minute 54;
		- Cesium-based globe; shows Australia; add layers for water pipes, trains,
		- Add all data in one place; then run simulation behind all the data that is georegistered; Terria.js allows you to build, as a wrapper on top of Cesium
- Need example of how this works with ESRI; how to add each kind of data
## 58:30 Example of using Chrome inspector to edit a web page in the browser
- using the "Inspector" , you can change any element on any web page using this tool in the Chrome browser. It works in Firefox, too. As you edit in the inspector, you can see what it will look like after each edit
- use inspector in Chrome to edit webpage on the fly: 59:00 ; use dropdowneditor to open inspector; windows open to the side; Examples:
		- Add CSI logo to the Terria website showing data for Australia New South Wales.; change the element linking to NSW logo to the CSI link to an image, a .png;
		- then use Cascading Style sheet; to alter the width and height of the CSI logo so it looks right.
- If we can master how to upload the UCBerkeley data in the right data catalog, we can create the Cesium website for the  UCBerkeley digital twin. 1:01:52

## Location of the Github cheat sheets that list all the interesting info for the various tools mentioned in the talks
- [Link to DR Github repository for instructions to create Digital Twin](https:///Github.com/dbrauchwerk/SRG_S23/wiki/Digital-Twins)
  or https://github.com/dbrauchwerk/SRG_S23/wiki/Digital-Twins 
- Complete guide to using PostGres as a relational database
- Excellent guide to PostGIS, showing the Python programs needed: https://postgis.net/workshops/postgis-intro
- For QGIS users, there is a JavaScript plugin for QGIS: QGIS2threejs; 
- click a button and export an interactive 3D from QQIS to an interactive display that you can share; put it on a website; 
- FEA javascript:  https://github.com/lge88/js-fea. or, better, https://mikolalysenko.github.io/femgl/index.html, this is the way to make the CSI website display many more images of pipes being tested to breaking points....a much richer display

- 
## Video
https://drive.google.com/drive/folders/1J9ReUou9oxdLAQyc_0KZqJIuQBl-y67T

97217
[http://he.net/3d-map/](http://he.net/3d-map/)

Semantic Scholar:
[https://pdfs.semanticscholar.org/d58c/8c51b99ea0c2fd0d6d094aac3966e349570f.pdf](https://pdfs.semanticscholar.org/d58c/8c51b99ea0c2fd0d6d094aac3966e349570f.pdf)
### Terria
[https://nsw.digitaltwin.terria.io/](https://nsw.digitaltwin.terria.io/)


### DR Github: 
[https://github.com/dbrauchwerk/dbrauchwerk.github.io](https://github.com/dbrauchwerk/dbrauchwerk.github.io)
