# Class 12 Reading Notes

## REST Status Codes

- 100’s = Tells the client that the header part of tghe info has been recieved
- 200's = Success codes that tell the client the request worked
- 300’s = Says the resource that the client is requesting isn't available
- 400’s = All error codes
- 500’s = Indicates a problem with the server
- What is a status code 202? Accepted. This code tells the client that the request was valid, but its processing will finish sometime in the future.
- What is a status code 308? Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.
- What code would you use if an update didn’t return data to a client? 204.
- What code would you use if a resource used to exist but no longer does? 410
- What is the ‘Forbidden’ status code? 403 The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## Video Questions

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env? Becasue we don't want people seeing where our server is located.
2. What is middleware? code that runs when the server makes a request but before it get passed to the route.
3. What does app.use(express.json()) do? Lets server except JSON as a body.
4. What does the /:id mean in a route? it means its a parameter
5. What is the difference between PUT and PATCH? Patch only updates on what the user passes us. PUT updates all of the information.
6. How do you make a default value in a schema? pass deafult in the as key.
7. What does a 500 error status code mean? Means there is an error on the server.
8. What is the difference between a status 200 and a status 201? 201 means successfully created and object while 200 means everything was succesfull

---

### Resources

[REST Error MSGs](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

[Rest Video](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

---

[Back to Home](../README.md)
