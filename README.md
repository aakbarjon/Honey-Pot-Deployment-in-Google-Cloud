
**Google Cloud Honeypot Deployment**


**Objective:** Create a honeynet using MHN-Admin.

### MHN-Admin Deployment


I have used GCP for MHN-Admin deployment. 
As you can see I have created two VMs. One for admin and the other for honeypot.

Gif Walkthrough:

<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment

Dionaea gets a copy of the malware with the help of malware trap.

Gif Walkthrough:

<img src="dionaea-honeypot.gif">

### Database Backup

MHN-Admin uses mongodb. JSON has a record of Sensor database of attacks that I have received from MHN-admin terminal.





