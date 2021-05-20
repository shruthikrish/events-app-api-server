# Sample API Server - with both Stateful & Stateless storage 
## Technology
* NodeJS version 12.14.1 or greater as the Server
* Express for RESTful Routes
* Morgan for Logging
* Mocha, Chai, NYC for Testing  
* Google Cloud Firestore NoSQL for persistent storage

## Instructions
* Check the version of node with ` node -v`  
if it is less than 12.14.1 use nvm to install version 12.14.1  
You can check if you have nvm installed with `nvm -v`  if this returns the version of nvm  
you can then use  `nvm install 12.14.1`  
If you don't have nvm installed I suggest that you install it because it is by far the easiest way to switch between versions of NodeJS.  
* Run ` npm install ` to load the dependencies.  
* Now `npm start` will start the server on `port 8082`  

## Starting Point  
Simple API server using Google Firestore for persistent storage. Data will be stored in an array on the server if environment variable TESTING is true, otherwise the events will be stored in a Firestore NoSQL DB.
