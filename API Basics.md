# API (Application Programming Interface) -
- An API (Application Programming Interface) is a set of rules, protocols, and mechanisms that allows one software application to communicate with another software application.

# Core Components -
## 1. Request & Response -
- Every API interaction follows this pattern:
### Request -
- Client sends a request (what do you want?). The client can be: Browser, Mobile app, Frontend application, Another server, CLI tool and Automation script
- **Structure of an API Request:**
- A request usually contains:

| Component  | Purpose                |
|------------|------------------------|
| URL        | Where request goes     |
| Method     | What action to perform |
| Headers    | Extra metadata         |
| Body       | Data being sent        |
| Parameters | Additional values      |  

### Response -
- Server sends back a response (here it is, or here's the error)
- **Structure of an API Response:**

| Component   | Purpose     |
|-------------|-------------|
| Status Code | Result      |
| Headers     | Metadata    |
| Body        | Actual data |

## 2. Endpoint-
- An endpoint is a specific URL in an API where a client can access a resource or perform an action.
- It acts like:

      A destination
      An entry point
      A doorway to a service/resource

## 3. Method-
- HTTP Methods are actions that tell the server: "What operation should be performed on the resource?"

| Method | Meaning      |
|--------|--------------|
| GET    | Read data    |
| POST   | Create data  |
| PUT    | Replace data |
| PATCH  | Modify data  |
| DELETE | Remove data  |

## 4. Headers-
- Headers are key-value pairs sent alongside every HTTP request and response. They carry metadata — information about the request/response, not the data itself.

## 5. Status Codes-
- HTTP Status Codes are responses sent by the server to indicate whether an API request was successful or failed.

| Code | Meaning                                   |
|------|-------------------------------------------|
| 200  | OK — Request successful                   |
| 201  | Created — Resource created successfully   |
| 400  | Bad Request — Invalid request from client |
| 401  | Unauthorized — Authentication required    |
| 403  | Forbidden — Access denied                 |
| 404  | Not Found — Resource does not exist       |
| 500  | Internal Server Error — Server-side issue |

# Http and Https -
- HTTP is a protocol that allows browsers and applications to communicate with web servers.
- HTTP is a communication protocol used to transfer data between:
  -  Client (Browser/App)
  - Server (Website/API Server)
- It is the foundation of web communication.

### https-
- HTTPS is the secure version of HTTP.
- HTTPS encrypts data transferred between client and server.
- 

# Types of API-
## 1] REST API -
- REST is not a protocol, it's an architectural style (a set of rules/constraints). Any API that follows these rules is called a RESTful API.
- Created by Roy Fielding in his 2000 PhD dissertation.
- Uses HTTP as the communication protocol.
- Data exchanged usually in JSON (sometimes XML)
- **Client-Server Architecture-** Frontend and backend separated. Client Server evolve independently. Change the UI without touching the API. Scale the backend without touching the frontend.
- **Stateless-** Each request is independent. Server does NOT remember previous requests. Every request contains all required information.
- **Cacheable-** API responses can be stored temporarily and reused instead of requesting data again from the server. This improves Speed, Performance and scalability.
- **Uniform Interface-** All REST APIs should follow a consistent and standardized way of communication.

## 2] GraphQL API -
- GraphQL is a query language for APIs and a runtime for executing those queries.
- Developed by Meta(Facebook) in 2012 and open-sourced in 2015.
- GraphQL allows clients to request exactly the data they need from the server.Unlike REST APIs, GraphQL usually works through one single endpoint.

## 3] WebSocket API -
- WebSocket is a communication protocol that enables real-time, two-way (full-duplex) communication between a client and a server over a single persistent connection
- **Real-Time Communication:** Data transfer happens instantly.
- **Persistent Connection:** Single connection remains open.
- **Full-Duplex:** Both sides communicate simultaneously.
- **Low Latency:** Very fast communication.
- **Reduced Overhead:** No repeated HTTP headers in every request.

## 4] SOAP API-
- SOAP stands for Simple Object Access Protocol.
- SOAP is a protocol used to exchange structured information between applications over a network.
- **XML-Based:** SOAP messages are written only in XML format.
- **Protocol-Based:** SOAP follows strict rules and standards.
- **Platform Independent:** Works with different programming languages:Java, Python, .NET, PHP etc.
- **Highly Secure:** Supports: Authentication, Encryption, Digital signatures and WS-Security.










