# API Tester

A simple [API Tester](https://erikdevelopment.github.io/API-Test-Tool/) that allows you to send HTTP requests (GET, POST, PUT, DELETE, PATCH) to any endpoints and view the response in real-time. The tool also provides functions for authentication, file upload, and header as well as body management.

## Features

- **Select HTTP Methods**: Send GET, POST, PUT, DELETE, or PATCH requests.
- **Custom Headers**: Add custom headers in JSON format.
- **Request Body**: Define the body for POST/PUT/PATCH requests.
- **File Upload for Authentication**: Upload a file to enable authentication.
- **Username and API Key**: Optional text fields for username and API key for authentication.
- **Responsive**: Works on both desktop and mobile devices.

## How to Use

1. **Select HTTP Method**: Choose one of the available HTTP methods (GET, POST, PUT, DELETE, PATCH) from the dropdown list.
2. **Enter API URL**: Input the URL of the desired API endpoint into the text field.
3. **Add Headers**: Input custom headers in JSON format. Example:
   ```json
   {
     "Content-Type": "application/json"
   }
   ```
4. **Request Body (Optional)**: Input the body of your request (e.g., JSON) for POST/PUT/PATCH requests.
5. **File Upload for Authentication**: Select a file to upload (optional, depending on API requirements).
6. **Username and API Key**: Optionally, enter a username and API key for authentication.

Click the **"Send Request"** button to submit the request. The response will be displayed in the lower section, including:

- **Status Code** (green or red, depending on success or failure)
- **Response Headers**: The headers of the response in JSON format
- **Response Body**: The content of the response in JSON format (if successfully fetched)
