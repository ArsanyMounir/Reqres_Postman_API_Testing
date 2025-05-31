# Reqres API Testing with Postman

This project contains a Postman collection designed to automate API testing for the Reqres service. The tests cover essential user management endpoints, including authentication, user creation, retrieval, update, and validation of responses.

## 🚀 Project Overview

The goal of this project is to validate the functionality of Reqres APIs by:

- Testing login and token extraction workflows  
- Creating and updating user data dynamically  
- Retrieving single and multiple user details  
- Asserting response data correctness using Postman test scripts  
- Parameterizing base URLs and request data for flexibility and reuse  

## 📂 Collection Contents

- **List User**: Retrieves a paginated list of users.  
- **Create User**: Creates a new user with dynamic data.  
- **Single User**: Fetches details of a specific user by ID.  
- **Single User Update Test**: Validates user update API, checking for key fields and data correctness.  
- **Login**: Simulates user login to extract authentication token.  
- **Update**: Updates user details and validates status codes.

## ⚙️ Key Features

- **Parameterized Environment Variables**: Uses `{{BaseURL}}` and other variables to support different environments and test data.  
- **Response Assertions**: Scripts validate key response fields such as `id`, `email`, `first_name`, and `last_name`.  
- **Token Extraction & Reuse**: Extracts tokens dynamically to authorize subsequent requests.  
- **Comprehensive API Coverage**: Covers CRUD operations and authentication workflows.

## 📋 How to Use

1. Import the provided Postman collection into your Postman client.  
2. Set the environment variables (e.g., `BaseURL`, `userIdUpdate`) as needed.  
3. Run requests individually or use Postman’s Collection Runner for automated execution.  
4. Review test results in the Postman Tests tab for each request.

## 📈 Outcome

This suite provides a robust foundation for automated API testing of Reqres, ensuring reliability and correctness across all user-related endpoints with reusable and maintainable test scripts.

