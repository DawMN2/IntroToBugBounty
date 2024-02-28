<span style="color:#00b0f0">this course is presented by Abdullah(talson) </span>

the average amount of bounty most get is 500 dollar 
in bug bounty you don't need to have any previous experience 
http://testphp.vulnweb.com/
https://t.me/bugbounty_safcsp | this telegram channel will provide more about this course 
https://discord.com/invite/xhzH9Uynx3 | this the discord channel for the course 
==don't scan any webpage that is not in any platform or doesn't provide a bug bounty program ==
you need to give this a lot of time so you can gain back 

best platforms for bug bounty : 
- bug bounty sa
- HackerOne
- Intigriti
- etc.
not only website , there is also mobile app and desktop apps , hardware firmware and source code ai models and smart contract
-------------------------------------------------------------------------------

## <span style="color:#92d050">Methodology</span> 
### <span style="color:#ff0000">analyze and scope</span>
it is critical to understand the scope of the program that decide the culnerability that are acceptable
you need to read the rules and anything that is written in the description of the program to avoid any waste of time 
### <span style="color:#ff0000">valid target</span>
scanners are not always right to write about their vulnerabilities because there might be someone before you have tried it but you can also try it if it was an early access or you want to try your luck
#### <span style="color:#ff0000">choose a target </span>
- choose a program you are interested in 
- or choose the one you are experienced in 
- choose a program that you enjoy 
### <span style="color:#ff0000">fuzzing </span>
this steps is about trying your luck to find if the programmer forgot to fix some issue 
some of the known tools for fuzzing the web pages is [vaf.exe] , it fuzz the pages to find any 
don't scan or fuzz very hard so you won't be band
### <span style="color:#ff0000">proof-of-concept</span>
this the most important part where you explain the vulnerability and what is its impact 

### <span style="color:#ff0000">writing a good report</span>
- be clear 
- provide a clear and descriptive title 
- show the severity of the vulnerability 
- provide a clear summery 
- give a clear steps to reproduce 
- provide a poc 
- recommend a mitigation
- validate the report 
- the report may have a video or images 
- some time the good report may get a bit more on the reward 
### <span style="color:#ff0000">reporting tips</span>
- don't give assumption 
- always keep the reader in your mind 
- be professional (don't speak like in street)
- build a relationship with the team by helping the team to fix the issue
- get a strong relationship with the developers and have respect with them by always submitting a validate report (not spamming by looking always for the stats of the report or varbal abuse)
- support the security team till they fix the issue 
- communicate with the organization as they prefer 
- report stats : 
- need more info 
- informative 
- duplicative
- triaged (the tesam found it)
- resolved (there is a report about it)
- execute the vulnerability the amount that allow you to explain the vulnerability
### <span style="color:#ff0000">why failing some time </span>
- wrong programs 
- so stick with the program 
- you don't do recon 
- you only go for low-hanging fruit 
- try to get into private programs (less crowded)
### <span style="color:#ff0000">why the report was refused </span>
- you didn't read the policy 
- you didn't think like the organization you are a hacker (different priorities)
- you always report the first minor bug you find 
- you write bad reports
### <span style="color:#ff0000">what to do when stuck </span>
- teak a break 
- build a new skill set 
- gain a fresh perspective 
### **==be patinet, you can't always find a bug==**

### <span style="color:#ff0000">how to develop yourself</span>
- understand networks 
- you can also get eWAPT
-------------------------------------------------------------------------------
## <span style="color:#92d050">how does the web work </span>
### <span style="color:#ff0000">http basic :</span> 
- the http header is made of four things : 
- the method (get , post...) 
- GET : to get the page
- POST : to send request 
- HEAD : like get but no body 
- the url (the path the page the is requested) 
- the protocol version (the protocol used to communicate with the server)
- the body (the data the server provide or get)
- user-agent : for the developer purpose so the user can get the best result
- THE RESPONSE THE SERVER RESPONES : 
- the status code : the status of the request in number like 404
#### <span style="color:#ffff00">http proxy </span>
is server between the client and the real server, it is used to intercept the request or the response
most famous one : 
- burp suite 
- zap proxy 
- the bowser develop tool

### <span style="color:#ff0000">an example to apply for proxy </span>
run burp suite 
set the target on the target page
the issue page is good to find how to exploit the vulnerability 

-------------------------------------------------------------------------------
for the word press use wp-scan to scan the site 