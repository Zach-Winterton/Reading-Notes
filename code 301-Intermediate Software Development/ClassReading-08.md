# API's

[home](/README.md)

## API Design Best Practices

### What does REST stand for?
Representational State Transfer

### REST API's are designed arouns a -------?
Resources, which are any kind of object, data service that can be accessed by the client.

### What is an identifer of a resource? Give an example:
It is the URI that uniquely identifies that resource
Https://retail-outlet-mall.com/orders/1

### What are the most common HTTP verbs?
GET, POST, PUT, PATCH and DELETE

### What should the URIs be based on?
Resource URI's should be based on nouns (the resource) and not verbs

### Give an example of a good URI?
https://retail-outlet-mall.com/orders

### What does it mean to have a 'chatty' web API? Is this a good or bad thing?
All web requests impose a load on the web server. The more requests, the bigger the load. Chatty web APIs that expose a large number of small rsources. Such an API may require a client application to send multiple request to find all of the data that it requires.

### What status codes does a successful GET request return?
It typically returns status code 201

### What status code does an unsuccesful GET request return?
If the resource cannot be found, the method should return 404 (not found)

### What status code does a successful POST request return?
It returns HTTP status code 201. It could also return 200 or 204 but 201 is completely created


### What status code does a successful DELETE request return? 
If successful it should return a status code of 204

## Regexr

### How would you match your name using RegEx?
Zach
^[a-zA-Z]+$

## Things I want to know more about
