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

