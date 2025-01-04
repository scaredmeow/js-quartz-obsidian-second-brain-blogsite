---
draft: false
tags:
  - backend
  - API
  - Restful
---

An **API (Application Programming Interface)** is a way for two systems or applications to communicate and exchange information. APIs act as a bridge, allowing different software components to interact without knowing how each one works internally. For example:

- A weather app uses an API to fetch real-time weather data from a remote server.
- A payment gateway like PayPal provides APIs for online stores to process payments.

APIs simplify integration, enabling developers to build more complex applications by leveraging existing services.

### What are the Types of API Protocols?

APIs can use various communication protocols, including:

1. **[[REST (Representational State Transfer)]]**:
    - Most common.
    - Stateless, meaning each request from the client contains all the information needed to process it.
    - Uses HTTP for communication.

2. **SOAP (Simple Object Access Protocol)**:
    - A stricter protocol with XML-based messaging.
    - Common in enterprise systems for high-security transactions.

3. **GraphQL**:
    - Flexible query language allowing clients to specify the exact data they need.
    - Commonly used for modern apps.

4. **gRPC**:
    - Efficient binary protocol for high-performance APIs.
    - Often used in microservices and real-time communication.

5. **WebSockets**:
    - Enables full-duplex communication for real-time apps like chat or live notifications.

### What are HTTP Methods?

HTTP methods are verbs used to tell an API what action to perform:

- **GET**: Retrieve data (e.g., `GET /users` for a list of users).
- **[[POST]]**: Create new data (e.g., `POST /users` to add a new user).
- **PUT**: Update existing data completely (e.g., `PUT /users/123` to replace user data).
- **PATCH**: Update part of the data (e.g., `PATCH /users/123` to change a user's email).
- **DELETE**: Remove data (e.g., `DELETE /users/123` to delete a user).

### What is the Structure of a Typical API Endpoint?

A typical API endpoint consists of:

1. **Domain**: The base address of the API (e.g., `https://api.example.com`).
2. **Path**: Specifies the resource (e.g., `/users` or `/users/123`).
3. **Query Parameters**: Key-value pairs to filter or customize the request (e.g., `/users?age=25`).
4. **Headers**: Metadata about the request, such as `Authorization`, `Content-Type`, or `Accept`.
5. **Body**: Used with methods like `POST` or `PUT` to send data in JSON or other formats.

Example:

```bash
curl -X GET "https://pokeapi.co/api/v2/pokemon?limit=2&offset=0"
```

Result:
```json
{
  "count": 1302,
  "next": "https://pokeapi.co/api/v2/pokemon?offset=2&limit=2",
  "previous": null,
  "results": [
    {
      "name": "bulbasaur",
      "url": "https://pokeapi.co/api/v2/pokemon/1/"
    },
    {
      "name": "ivysaur",
      "url": "https://pokeapi.co/api/v2/pokemon/2/"
    }
  ]
}
```

- **Domain**: `https://pokeapi.co`
- **Path**: `/api/v2/pokemon`
- **Path Parameter**: `v2`
- **Query Parameter**: `limit=2&offset=0`
- **HTTP Method**: `GET Method`
	- `-X GET`: Specifies the HTTP method (GET is the default, so this part is optional)

### What are Status Codes?

Status codes indicate the result of an API request. Common codes include:

- **2xx**: Success
    - `200 OK`: Request succeeded.
    - `201 Created`: Resource created.
- **4xx**: Client Errors
    - `400 Bad Request`: Invalid request.
    - `401 Unauthorized`: Authentication required.
    - `404 Not Found`: Resource not found.
- **5xx**: Server Errors
    - `500 Internal Server Error`: Something went wrong on the server.

```bash
curl -X GET "https://http.cat/102.jpg" --output 102.jpg
```

