# Class 8 Reading Notes

## API Best Practices

1. What does REST stand for? REST Stands for Representational State Transfer.
2. REST APIs are designed around resources,.
3. What is an identifier of a resource? Give an example. An identifier is a URL that uniquely identifies that resource. EX: https://adventure-works.com/orders/1
4. What are the most common HTTP verbs? GET, POST, PUT, PATCH, and DELETE.
5. What should the URIs be based on? Resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource)
6. Give an example of a good URI. EX: https://adventure-works.com/orders
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? "Chatty" web APIs expose a large number of small resources. Bad thing.
8. What status code does a successful GET request return? returns HTTP status code 200
9. What status code does an unsuccessful GET request return? return 404
10. What status code does a successful POST request return? HTTP status code 201 .
11. What status code does a successful DELETE request return?  HTTP status code 204 (No Content)

---

### Resources

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

---

[Back to Home](../README.md)
