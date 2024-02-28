3target to practice
testphp.vulnweb.com

-------------------------------------------------------------------------------
## <span style="color:#92d050">target</span>
### <span style="color:#ff0000">site map</span>
this page well show you where have you been redirected and where have you been
### <span style="color:#ff0000">issue definition </span>
here you can find how to exploit the vulnerability 

-------------------------------------------------------------------------------
## <span style="color:#92d050">Proxy</span>
### proxy settings 
if you don't to be bothered use this tab to set the rules of interception to be in the scope so the other sites requests don't get in the way 

### <span style="color:#ff0000">interceptor</span>
here you can run the interceptor to intercept the request or the response 

don't forget to check the certificate of the burp suite by the browser  on http://burp then import the certificate to the browser 

set proxy of the browser to the IP of the burp suite proxy 
or use foxy proxy 

you can modify the header and forward the request 
### <span style="color:#ff0000">HTTP history</span>
will show you the responses and the requests before 
you can render the page to see how was it 

-------------------------------------------------------------------------------
## <span style="color:#92d050">Intruder</span>
## <span style="color:#ff0000">Position </span>
here you can modify the request however you want to attack as a fuzzier
### <span style="color:#ff0000">Payload</span> 
you can write list or copy paste it to attack using the header in the position 
### <span style="color:#ff0000">Result</span>
no need to explain this page 

## <span style="color:#ff0000">Repeater</span> 
get the page from the interceptor and repeat the request with the ability to stop and start every time 

-------------------------------------------------------------------------------
## <span style="color:#92d050">Decoder</span>
this page is used to decode and code any string provided so you won't need to visit any webpage or use a tool 