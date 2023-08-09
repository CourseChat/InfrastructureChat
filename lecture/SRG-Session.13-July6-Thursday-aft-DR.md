---
aliases: 
publish:
---

%%
date:: 2023-07-10 Monday
parent::
%%
# Rebuild PC's from scratch to install latest version of Linux; Build new CSI website; buy domain; publish
## Buy  global domain for CSI  website to hold all projects
- Multiple attempts to wipe PC's in room 305 Davis;
	- Discovery of USB Port difficulties
- Demonstration of Raspberry Pi-based single board Linux computer: 10:11: 13:44
	- performance similar to PC desktops, but ARM based
	- show how to architect a new site; security discussion
		-  64 GB of memory on single board; add 2TB disk later

 13             | 2023-07-06 Thu morn      

## Video- 3:12:00
https://drive.google.com/drive/folders/1aG3Q4LrLy7N_SHzOOvQkeXGgjNCmtQIj
4605
## Transcription: 
- https://drive.google.com/drive/folders/1-4KNeaE-J3dYYsqPdhGZXLS-wHLlDvdI

## Outline

- Demonstrate building a complete website, hosting it on a solar-powered server mounted on a pole at CSI at the Richmond Field Station

### Build a computer
- since CSI does not have computer power at moment, use Raspberry Pi to deploy our software projects; 
	- CSI Chatbot
	- Digital Twin
	- Sustainabilty Chat
	- Courseware Chats
	- National Science Foundation Chats
- we will learn how to deploy complete software environments: use Docker containers

### example software for 3D GIS : TerraJS
- TerraJS: we will run our own GIS 3D display of all Digital Twin resources
	- Open source framework for web-based geospatial catalog explorers
- Get Docker container: contains all needed software:   webservers, databases, application programs, to run 
- How to connect this single board computer to the internet so anyone, anywhere, can connect to this directly? 
- if we build a solar powered server that runs off a battery, charges itself, that costs less than a hundred bucks, that means you can basically have a computer that you can put anywhere and can offer information of any type, geospatial or otherwise for free.
- If you added a Starlink dish, which is, you know, 150 bucks a month for the service,  then you can provision a site anywhere on earth.
### Installing PostGres, PostGIS
- Here's a container to install PostGIS; this allows us to have our own geocoder, store all our geodata, calculate the lat-long for any address, so when we ask questions of our database, it can perform calculations to find which things are closest to each other.  As for the EBMUD PipeChat.  All installed with one line of code.
- H-top...what's running on the machine;
- Now, deploy a PostGres database from Docker;
- All of this on Linux: Linux is basically, take a kernel,  add a package manager and a window manager. The thing that moves the windows around, that's the window manager.
The Package manager is the thing that installs the software . Now you have an operating system.
There's a whole library of software called packages that you can install directly from the people that provide  a distribution, which is the combination of all three of those things.
That's it.
- Be sure to learn the little tricks, like "Autocomplete", so it types for you.
- Now, we also installed Jupyter on this single-board computer.  So it will just run Jupyter notebooks.
- Import Pandas....run a JN....
- Now all of you are going to do this on your own machine.  I want you to set up I-Librarian.
- Now, we're logged in on the single-board computer.  Run I-Librarian
	- This is used to run research groups, it's how you share journal articles and academic articles amongst the group, and everybody can take notes, we can annotate them we can create bibliographies.

It's going to be something that helps us share all the information that we need to have as well to build the things we're about to build.

- Everyone now, use your computer to connect to this single-board computer. We do it using SSH

### Using SSH to connect to any computer
- Create an encrypted connection from your machine to this machine
- Remember about IP addresses: we're going to turn on SSH and VPN, which you will need at some point wherever you are in the world, to reach the rest of the world.
- What if we could punch a hole in the network and then communicate to a different system somewhere around the internet, and then all of us connected that system out on the internet, which will then punch a hole back through the Berkeley network and then communicate.
- the role of the IT folks is to try and create a series of, particularly like sort of walled gardens where things can talk to each other, so that only the right things talk to the right things, and invariably, it's kind of like, kind of impossible, because there's so much stuff, there's so many things to play into, and then when you wanna use something, you're not trying to do something wrong, you're trying to get on Slack, or you're trying to hook a server up here, you can't make it work.
- And so over the last couple of years, this has all changed, and there's different philosophy about doing this, and the people that specialize in cybersecurity, people like the NSA, National Security Agency, or CISA, the Cyber Infrastructure Security Agency, who are responsible for these things, and I'll show you what these things look like.
- They actually operate more computers than probably anyone in the world, probably a fair guess.Mostly, they listen to people talking, all right? 
- And then CISA, CISA is a newer agency, I think they're part of Homeland Security, and they are responsible for coordinating with the public, and businesses, and the government, when there is some sort of cyber attack, or cyber incident.
- Click here...click *learn more*, and they publish these really interesting reports, that will tell you basically what hackers are doing inside the United States, or against the United States.
- So if we wanna get around some kind of, say as a government's totalitarian filtering of the internet, or we wanna maybe connect to our machine inside of Berkeley network, from out on the internet somewhere, what we can do is we can use Cloudflare as network, and we connect to one of the blue dots. Cloudflare has servers everywhere.
- we're gonna use something called, it's now called Zero Trust. This is the new security model. It replaces what EBMUD uses....firewalls.
- we're gonna use our Google accounts to prove that we are who we say we are.
- the way that everything's going, the zero-trust stuff, is we connect everything in a big mesh. And if everything has to prove, you have to prove that you are who you say you are.
- Zero trust security is an IT security model that requires strict identity verification for every person in device trying to access the resources under private network, regardless of whether they're sitting within or outside the network provider.
- So does everybody have multi-factor authentication to enable their Google account? Yes, no, yes, no. Okay, you should.
- Let's buy a domain. So, we know what domains are, right? What we're gonna do is we're gonna find domain name we like.
   So, if I go to domain registration and I register a domain, what do I want our thing to call? We said XO1SRG.net. Cool.
   All right, it's 10 bucks.
- If somebody comes and attacks your website, Cloudflare is one of the few people that can actually stop it from happening.
- type in EX01SRG.NET.  What do you see?  Our new website.
- 
-  

 