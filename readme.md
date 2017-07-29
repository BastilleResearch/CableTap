# CableTap

Public advisories, white paper, and slide deck, for CableTap: Wirelessly Tapping Your Home Network, as presented at DEF CON 25. 

Marc Newlin  
marc@bastille.io  
@marcnewlin  

Logan Lamb  
logan@bastille.io  

Chris Grayson  
chris@websight.io  
@_lavalamp  

## Documents 

[DEFCON-25-Marc-Newlin-CableTap-Slides.pdf](doc/pdf/DEFCON-25-Marc-Newlin-CableTap-Slides.pdf)  
[DEFCON-25-Marc-Newlin-CableTap-White-Paper.pdf](doc/pdf/DEFCON-25-Marc-Newlin-CableTap-White-Paper.pdf)  
[Vulnerability Details](doc/advisories)  

## Tools

[fastcgi_fingerprint.nse](src/fastcgi_fingerprint.nse)  
Nmap NSE script for identifying FastCGI services  

[management_request](management_request)  
Binary file that can be used with ZGrab to identify FastCGI services. The command is invoked as follows:  

```zgrab --port 1026 --input-file targets --data management_request --output-file zgrab_1026.json --timeout 3```

## Resources

[https://bastille.net/research/vulnerabilities/cabletap/](https://bastille.net/research/vulnerabilities/cabletap/)