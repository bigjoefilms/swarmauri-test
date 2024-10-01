# Endpoints
##User Endpoints


#### Get Current User
Endpoint:

```

GET /v1/users/me

```
**Description**: Fetches the details of the currently authenticated user.

Response:

```
{
  "id": "12345",
  "email": "user@example.com",
  "name": "John Doe"
}
```


#### Create User

Endpoint:

```

POST /v1/users
```
**Description**: Creates a new user in the system.

Request Body:

```
{
  "email": "newuser@example.com",
  "password": "password123"
}
```

Response:
```
{
  "id": "67890",
  "email": "newuser@example.com",
  "created_at": "2024-09-01T12:00:00Z"
}
```
#### Data Endpoints

1. Upload Data
Endpoint:

```
POST /v1/data/upload
```

**Description**: Uploads a dataset for processing by the AI engine.

Request Body:

```
{
  "dataset_name": "sample-dataset",
  "file": "file_contents_in_base64"
}
```

Response:

```
{
  "status": "success",
  "dataset_id": "abc123",
  "uploaded_at": "2024-09-01T12:00:00Z"
}
```
