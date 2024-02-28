# <span style="color:#92d050">XSS</span>
it is used for multiple reasons
- impersonate the others 
- carry out any action that the user is able to perform 
- read the user's login info 
- perform virtual defacement (manipulate the web 'face')
- inject trojan functionality into the web app 
where you can learn how to perform it : 
- portswigger.net
[xss.report] : is a useful site that will give you xss payloads and where it was performed before and can also give you the ability to upload a malicious payload and give you the results for it
[https://github.com/payloadbox/xss-payload-list] : a github repo that contain some xss payloads you can perform 
==if the site doesn't filter the payload it is considered to be xss vulnerability==

## <span style="color:#ff0000">self xss</span>
the xss vulnerability is only affecting you but you exploit it for anyone else 
it is not accepted in most bug bounty programs 
## <span style="color:#ff0000">reflected</span> 
where the malicious script comes from the current http url 

you can write an html code that well represent the page again and in advance you can make it load for you sensitive files or using java script you can make it show you an alert containing the the file contents 
## <span style="color:#ff0000">stored</span>
the malicious script is stored on the server after being performed 

some time the payload can be a reflected type but if there is a way to upload it to the server it will be identified as a stored xss 
## <span style="color:#ff0000">DOM-based</span>
it is the same as reflected xss but it differ in where it gets executed
## <span style="color:#ffff00">practice</span>
you can use the room DVWA on tryhackme.com to practice this vulnerability
you need to first change the level of the challenge from impossible 
some examples:
- \<script>alert(1)\</script> : low
- \<scr\<script>ipt>alert(1)\</scr\<script>ipt> : medium
- \<scriPt>alert(1)\</scrIpt> : medium
- find more in : [https://portswigger.net/web-security/cross-site-scripting/cheat-sheet]
- xss filter evasion
- if you are looking to test your code use the developer tool on the browser in console page
- tip : if you can use alert use console.log() and you can find the result in the console page from the developer page 

you can also use the labs in portswigger.net to practice more, but you need to register first 

you can also use [[burpsuite]] to intercept the request and modify it, and remember to forward the google api request 



-------------------------------------------------------------------------------
# <span style="color:#92d050">how url works </span>
the first part of the usl is the domain name 
the second part is the parameters and you can separate it with the "&" character 
and exploiting this could be with injecting some command or some wrong values 

you can also some time use the url to download the file from the server and in the idor vulnerabilty you can also access file through the url that is not allowed to be accessed 

-------------------------------------------------------------------------------
# <span style="color:#92d050">IDOR</span>
this vulnerabilty is for when you are allowed to download file that is not allowed to access by you or only for admin
in this kind of situation the developer most use the whitelist (some allowed and the rest is not) no the blacklist (some is allowed and the rest is allowed)
## <span style="color:#ff0000">information disclosure type</span>
where the information of the users ot the sinsetive information is accessable or the techneqal information about the website is exposed 
also the source code and the passwords for the admin or root account maybe is in the source code as a comment
the error messages is also considered to be disclosure information because it can contain a lead to another vulnerabilty that can have a great impact
in the error type the vulnerability the website may expect an integer from the user but if you give it a string it may disclose an info from the server 
for backup disclosure you can try look for the files with the extension of .bak
## 