Skip to content
NAVEENMATHIVANAN
/
InformationGathering

Type / to search

Code
Pull requests
Actions
Projects
Security
Insights
Owner avatar
InformationGathering
Public
forked from gowriganeshns/InformationGathering
NAVEENMATHIVANAN/InformationGathering
 1 branch
 0 tags
This branch is 3 commits ahead of gowriganeshns:main.
Latest commit
@NAVEENMATHIVANAN
NAVEENMATHIVANAN Update README.md
100b808
on Jun 20
Git stats
 5 commits
Files
Type
Name
Latest commit message
Commit time
README.md
Update README.md
2 months ago
README.md
Information Gathering Techiques

To perform information gathering techniques
AIM:
To perform information gathering techniques using kali linux

STEPS:
Step 1:
Install kali linux either in partition or virtual box or in live mode

Step 2:
Investigate on the various categories of tools as follows:

Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

OUTPUT:
image

Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in
OUTPUT:
finding

FINDING HOST COMPANY:
get further detail by using ip2location.com website.

OUTPUT:
image

History of the website:
OUTPUT:
https://web.archive.org/

image

Webserver Fingerprinting:
Netcat:
nc 172.17.52.118 80
OUTPUT:
image

image

image

nmap:
nmap -p 21 -sV --script=banner ftp.vim.org
OUTPUT:
Screenshot 2023-06-20 112235

Whatweb:
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
OUTPUT:
image

image

httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
OUTPUT:
image

Tracing the Location:
TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in
OUTPUT:
image

UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in
OUTPUT:
image

ICMP Traceroute:
sudo traceroute  www.saveetha.ac.in
OUTPUT:
image

RESULT:
The information gathering techniques tools/procedure were identified successfully

About
Information Gathering Techiques

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 57 forks
Report repository
Releases
No releases published
Packages
No packages published
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
