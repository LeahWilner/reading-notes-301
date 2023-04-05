# Class 8  

## API Design Best Practices

1. What does REST stand for?  
Representational State Transfer  

2. REST APIs are designed around a ____.  
resource  

3. What is an identifier of a resource? Give an example.  
a resource is any kind of object, data, or service that a client can access such as a customer order. The order number would be the identifier. 

4. What are the most common HTTP verbs?  
GET, POST, PUT, PATCH, and DELETE  

5. What should the URIs be based on?  
nouns (the resource)  

6. Give an example of a good URI.  
`https://axs.com/orders`  

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
Chatty web APIs expose a large number of small resources, its bad because it takes multiple requests to find all of the data  

8. What status code does a successful GET request return?  
200 (OK)  

9. What status code does an unsuccessful GET request return?  
404 (Not Found)  

10. What status code does a successful POST request return?  
201  (Created)

11. What status code does a successful DELETE request return?  
204 (No Content)  
