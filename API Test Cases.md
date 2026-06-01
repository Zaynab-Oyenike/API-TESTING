# API Test Cases

## API_TC_001

### Title

Verify Successful Retrieval of User Details

### Request Type

GET

### Endpoint

https://jsonplaceholder.typicode.com/users/1

### Objective

Verify that the API successfully returns user details for a valid user ID.

### Test Steps

1. Open Postman.
2. Create a new GET request.
3. Enter the endpoint URL.
4. Click Send.

### Expected Result

* Status code should be 200 OK.
* User details should be displayed in the response body.

### Actual Result

User details returned successfully.

### Status

Passed




## API_TC_002

### Title
Verify Invalid User ID

### Request Type
GET

### Endpoint
https://jsonplaceholder.typicode.com/users/999

### Objective
Verify the API response when a non-existing user ID is requested.

### Test Steps
1. Open Postman
2. Create a GET request
3. Enter the endpoint URL
4. Click Send

### Expected Result
The API should return an error indicating that the requested user does not exist.

### Actual Result
The API returned a 404 Not Found status code.

### Status Code
404 Not Found

### Status
Passed


