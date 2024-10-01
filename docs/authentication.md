
## Authentication

All requests to the AI Product API must be authenticated using API keys. You can generate an API key from your dashboard.


### Request Example

```
http
GET /v1/users/me HTTP/1.1
Host: api.ai-product.com
Authorization: Bearer YOUR_API_KEY
```

## Response
```
  json                                                                                      
        {
        "id": "12345",
        "email": "user@example.com",
        "name": "John Doe"
        }
```        

To authenticate, include the **Authorization** header with the value **Bearer YOUR_API_KEY**.  