## <span style="color:#92d050">what to recon</span>
- identify the target 
gather information about the target like the domains and the subdomains
the IP address and whois lookup : who.is
dns enumeration 
- web server fingerprint 
identify the software 
use nmap to find that 
- directory and file enumeration 
use disearch and gobuster 
look for common files like robots.txt
check for public resources like on github 
- spidering and crawling 
hakrwasler and burp suite and zap 
- public gathering using google dorks or google and shodan 
look for any cves for the services running and find how to exploit it 
- content discovery and subdomain enum 
use subfinder and amass 
- network and port scanning using nmap 
- identify the tech used and the frameworks 
look for the cms 
- search for public exploits 
search through the exploit db 
### <span style="color:#92d050">recon tools</span>
https://github.com/vavkamil/awesome-bugbounty-tools
[bugbountyhelper]
https://dorks.faisalahmed.me/#
[bgp.he.net] : for asn lookup ==(the asn is a block of IPs for the target owner)==
[hackertarget.com]
[crunchbase.com] : to see who have acquired this target
==it is always good to use proxy or vpn so you can avoid the ban on your IP==
- <span style="color:#ff0000">wappalyzer</span>
this is an extension for the browser that analyze the web page every time you get into one 
- #### <span style="color:#ff0000">nmap</span> 
- #### <span style="color:#ff0000">shodan</span>
==it is good to use your edu email to get more benifits==
it can give information about the location of where the target is and the asn it belong to it 
look for shodan cheat sheet to get a better experience 
- #### <span style="color:#ff0000">amass</span>
this tool can find a lot of information for you 
it have two modes : enum,intel
linux : [amass intel --whois -d inter.co]/[amass enum -d inter.co]
- #### <span style="color:#ff0000">whatweb</span>
- #### <span style="color:#ff0000">gobuster</span>
- #### <span style="color:#ff0000">hakrawler</span>
- #### <span style="color:#ff0000">ghdb (google dorks)</span>
how to use :
look for any query you think it will give you a useful results then add the target url or name 

for windows download the exe file and use as in linux 
