# CRUD

[home](/README.md)

# Reading
## Status Codes Based On REST Methods

### In your own words, describe what each group of status code represents:
<ul>
<li>100's = Informational response status code. Telling you to continue.</li>
<li>200's = Request was a success status codes</li>
<li>300's = Multiple choices redirect status codes</li>
<li>400's = Client error codes, invalid requests sent to a server</li>
<li>500's = These are server side error codes, ususally overwhelmed or unreachable servers</li>
</ul>

### What is status code 202?
Code tells the client that the request was valid but the processing will finish sometime in the future.

### What is a status code 308?
It is a permanent redirect. Tells the client ti use another URL to access the resource and not use the current URL anymore.

### What code would you use if an update didn't return data to a client?
I would use a status code of 204. It's the code for updates that don't return data to a client.

### What code would you use if a resource used to exsist but no longer does?
I believe I would use status code 307. Temporary redirect. It could become available again in the near future.

### What is the 'Forbidden' status code?
Status code 403 is the forbidden status. Client has no permissions to access the resource.

# Video

## Build A REST API With Node.js, Express & Mongo DB-Quick


### Why do we need to pull our Mongo DB database string out of our server and put it into our .env?
Because you will want to use something that isn't your local host.

### What is middleware?
It is software that allows communication between two or more applications.

### What does app.use(express.json()) do?
It recognizes the incoming request object as a JSON object. Method is called as a middleware in your application using app.

### What does the /:id mean in a route?
Its a paramater that we can access.

### what is the difference between PUT and PATCH?
PUT updates entire resource. PATCH updates partially

### How do you make a default value in a schema?
const subscriberSchema = new mongoose.Schema({
  name:
  type: string,
  required: true
  default:   .now
})

### What does a 500 error status code mean?
Error on server side. Error in database. It is not the client's fault.

### What is the difference between a status 200 and a status 201?
Status 201 is a more specific way of saying your request was successful and a resource was created. Everything is good.

## Things I want to know more about
