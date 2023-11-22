@# Ex-01-Simple-Web-Server
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
``
from http.server import HTTPServer, BaseHTTPRequestHandler

content= """
<html>
<head>
</head>
<body>
<h1>Welcome</h1>
</body>
</html>
"""

class HelloHandler(BasedHTTPRequestHandler) :
    def do_GET (self) :
        self.send response (200)
        self.send_header('Content.encode())


server_address= ('',80)
httpd = HTTPServer (server_address, HelloHandler)
http.server_forver()
``










## OUTPUT:
![Alt text](<Screenshot 2023-11-21 183320.png>)






## RESULT:
The program for implementing simple webserver is executed successfully.
