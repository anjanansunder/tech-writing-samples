# API Documentation – Sample Template

## GET /users

Retrieves a list of users.

### Request

```http
GET /api/v1/users HTTP/1.1
Host: api.example.com
Authorization: Bearer <token>
```

### Response

```json
[
  {
    "id": "12345",
    "name": "Jane Doe",
    "email": "jane.doe@example.com"
  }
]
```

### Response Codes
- 200 OK – Successful request
- 401 Unauthorized – Invalid token
- 500 Internal Server Error – Server failure
