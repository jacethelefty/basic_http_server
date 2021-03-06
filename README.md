#Basic HTTP Server

##Jason Montoya / Code Fellows JS 401

##To Submit this Assignment
  * fork this repository
  * write all of your code in a folder containing your name
  * push to your repository
  * submit a pull request to this repository
  * submit a link to your PR in canvas

##Description

For this assignment you should write an http server in vanilla node that responds to several different routes.

The server should respond to a request to /time that will send back the current time of the server.

It should also respond to a get request to /greet/name where name is any single word string. It should send back a string that greets that name.

It should also have a separate post request to /greet that takes the name in JSON format.


There should be tests using chaiHTTP for both routes, as well as a Gruntfile/package.json

##Rubric:
  * Tests: 4pts
  * Routes: 4pts
  * Organization and gulpfile/package.json 2pts

##References:

https://github.com/jacethelefty/create_an_http_server/blob/master/jack_sneed/server.js

https://github.com/jacethelefty/create_an_http_server/blob/master/walter_nicholas/server.js

https://github.com/jacethelefty/create_an_http_server/blob/master/john_tucker_miller/test/test.js


