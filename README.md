Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

### Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/c81736be-89d9-4c59-be4b-0310e703214a)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```
## OUTPUT:

![finding](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/81e82379-ca59-49ec-afad-f7cd5e2b50c3)


## FINDING HOST COMPANY:
get further detail by using ip2location.com website.

## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/6a193bb6-9c8f-42b0-913a-1efb863d5732)


## History of the website:
## OUTPUT:
https://web.archive.org/

![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/3dcca92f-cb96-4011-8a00-711a50a7259a)


## Webserver Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```
## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/891fed08-1c06-4524-b6bb-83cc66323eb6)

![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/3300afc8-9bf6-456e-a7dd-0a5e6aaed38d)

![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/d68d66ad-7f62-4d06-90f6-043c59551398)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## OUTPUT:
![Screenshot 2023-06-20 112235](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/2906cf6a-0987-40c3-abf3-cbc743a7b5bc)

## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```

## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/b2bdf1d8-29d4-4294-a45a-d1fa5a7f57e2)

![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/3d07050a-e1ee-4824-9b01-f162907d98e1)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/c6aa5b66-0821-47f8-9479-5272757cc358)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/3d810236-ecde-4842-8b1f-f739852d39a3)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/cc6fcdbb-3d45-4197-b020-dda080fac9e3)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/InformationGathering/assets/119394582/9741ee2a-60fa-4bff-8e87-b60f04321803)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
