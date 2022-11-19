# Honeypot Assignment

**Time spent:** 21 hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?
I have used GCP for MHN-Admin deployment. As you can see I have created two VMs. One for admin and the other for honeypot.


<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do? 
Dionaea gets a copy of the malware with the help of malware trap.

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

RDBMS is. JSON has a record of Sensor database of attacks that I have received from MHN-admin terminal





