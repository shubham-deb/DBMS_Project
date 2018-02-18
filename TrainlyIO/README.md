## PROGRAM NAMES AND THEIR FUNCTION: 
* server.js: This file imports all the libraries required to run the website on the browser. It also specifies the port number if we are running it on our local machine. 

* public/server/services/user.service.server.js: This file consists of all the queries that it sends to the database management system which is MySQL in our case. Based on the type of request (GET, POST, PUT, DELETE), it will fetch the data from DBMS and send the data back as the response.

* public/services/user.service.client.js: This file is used to manage the communication between the UI and the backend server. Based on the type of function being called from the UI, it sends a request (GET, POST, PUT, DELETE) consisting of the type of response expected back from DBMS. For example, if it sends a GET request, it expects the server to return data. Or if it expects UPDATE, it expects back either “OK” response or “ERROR” response from the server.

* views/common/templates: These are all common AngularJS templates used in our website.

* course/controllers, home/controllers, user/controllers: These are the controllers for our AngularJS templates. They are used to manage the control of flow of data between the Model(server) and View(AngularJS) template. Every controller will bind itself with the template so that dynamic changes in the UI could be shown on the template.

* home/ templates, user/templates: These are all the HTML pages of our website.

* public/config.js: This is the route provider for our AngularJS templates. Based on the url, it will return the appropriate AngularJS template as well as the controller.

* public/index.html: This is the starting page of our website which gets loaded when we start the website.

* express.js: This is used to import expressJS library for making REST API calls to the database from the server.

* package.json: it contains all the libraries which are required to run the database on the browser. We don’t have to download them from the websites as it will get automatically imported when we run it on our browser. 

## CREDENTIALS REQUIRED TO LOG INTO THE SYSTEM

Admin credentials : 
email : chang.chen2@husky.neu.edu 
password : 1234 

Student credentials : 
email : jack.daniel@gmail.com 
password : 1234 
