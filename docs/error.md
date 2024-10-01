##Error Handling

The API returns standard HTTP response codes to indicate success or failure. Common status codes include:

- **200 OK**: The request was successful.
- **400 Bad Request**: The request was invalid or cannot be processed.
- **401 Unauthorized**: Authentication failed or API key is missing.
- **404 Not Found**: The resource was not found.
- **500 Internal Server Error**: An error occurred on the server.

### Example Error Response

```json
{
  "error": "Invalid API Key",
  "message": "The provided API key is not valid.",
  "status": 401
}
```