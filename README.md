**question 2**
What is curl?
cURL is a computer software project providing a library and command-line tool for transferring data using various protocols.

**question 3**

HTTP Request:
curl www.google.ie

HTTP Response:
HTML from www.google.ie


HTTP Request:
curl -v http://odetocode.com/odetocode.jpg

HTTP Response:
> GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*
>
-------------------------
< HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Mon, 16 Sep 2019 09:28:13 GMT
<

**question 4**

HTTP Request:
curl http://www.jmarshall.com/easy/http/ --output html-easy.html

HTTP Response:
html-easy.html was downloaded, looks the same as https://www.jmarshall.com/easy/http/
however some hyperlinks do not work.

**question 5**
HTTP Request:
curl http://www.duckduckgo.com --output duckduckgo.html

HTTP Response :
duckduckgo.html was downloaded. the big difference was that the images and css were missing 
as they are seperate files.

**question 6**

HTTP Request:
curl https://www.duckduckgo.com/?q=science --output science.txt
curl https://www.duckduckgo.com/?q=science --output science.html
curl https://www.duckduckgo.com/?q=computer%20science --output computer-science.txt
curl https://www.duckduckgo.com/?q=computer%20science --output computer-science.html

HTTP Response :
html reponse shows search box but does not show anything that is brought in from external information for example 
search result, images or css.

**qustion 7**

HTTP Request:
curl -o gmit.json https://duckduckgo.com/?q=gmit&format=json

HTTP Response :
Should return gmit.json file, however it had to be done manually as it did not work on machine in lab.

**qustion 8**

irish times and independant have about 300 requsts each.

**Question 8**