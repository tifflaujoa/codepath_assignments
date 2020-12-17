# Honeypot Assignment

**Time spent:16 hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?

I used the GCP and in the Google Cloud Shell typed the commands to install a virtual machine instance. I created the MHN Admin and set up the firewall rules for that instance.

<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?

It is a scripting language used to attract attackers and captures malwares.

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?
SQL Databse. source ports, destination ports, type of honeypots, source ips, timestamps.

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*


## Notes

Describe any challenges encountered while doing the assignment.
I got confused with the ssh terminal and thought it meant the local bash terminal and spent hours figuring out where the errors come from, and finally found the ssh terminal on the GCP
