The **request body** is the body of the HTTP request that contains the data sent to the server. It is typically used with `POST`, `PUT`, and `PATCH` methods to send structured information.

#### **Format**:

Most APIs use **JSON** as the payload format because it’s lightweight, easy to read, and widely supported. However, payloads can also be sent as XML, plain text, or other formats.

#### **Example of a JSON Payload**:



```json
{     
	"name": "Bulbasaur",     
	"type": "Grass",     
	"level": 5 
}
```

#### **How Request Payload is Sent**:

1. Included in the HTTP request body.
2. Requires the `Content-Type` header to specify the format (e.g., `application/json`).

#### **Example cURL Command (POST with Payload)**:


```bash
curl -X POST "https://api.pokemon.com/v1/pokemon" \ 
-H "Content-Type: application/json" \ 
-d '{       
		"name": "Bulbasaur",       
		"type": "Grass",       
		"level": 5     
	}'
```

#### **Common Use Cases**:

1. **POST Payload**: Used to create a new resource.
    
```JSON
{     
	"title": "New Blog Post",     
	"content": "This is my first blog post!" 
}
```
    
2. **PUT Payload**: Used to update or replace an existing resource.
    
```JSON
{     
	"title": "Updated Blog Post",     
	"content": "I updated my blog post!" 
}
```