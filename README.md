# Express Basics 2 - Individual Practice

#### Create a basic web application with Express
* Create a module called ```birdModule.js``` with 2 functions, ```bawk()``` and ```chirp()```
* Using Express Router, in a separate file called ```routes.js``` add 3 routes:
```/``` which returns the text ```QUACK!```
```/chicken``` which returns the text ```BAWK!```
```/canary``` which returns the text ```CHIRP!```

Mount the routes in ```routes.js``` as ```/birds```

Example: Sending an HTTP GET request ```/birds/chicken``` should return ```BAWK!```

#### Extra
Add an additional route that lets the user pass in the name of a bird and haveyour app respond with ```Don't ruffle my feathers you BIRD!```  (where BIRD is the name/string passed in.
