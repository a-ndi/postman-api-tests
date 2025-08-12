# postman-api-tests
Postman collection demonstrating automated API testing with pre-request &amp; post-test scripts.

API Testing with Postman – [tutorial]

This project is a **Postman collection** that demonstrates API testing skills, including:
- Authentication handling
- Dynamic test data generation
- Automated pre-request and post-request validations
- Data-driven testing using Postman variables

- Project Overview
This Postman collection tests the APIs  
It covers:
- **Authentication Flow** – Automatically fetches and stores tokens.
- **CRUD Operations** – Create, Read, Update, Delete functionality.
- **Positive & Negative Testing** – Ensures endpoints behave as expected.
- **Performance Checks** – Validates API response time.

- Structure
- **Collection-Level Pre-request Scripts** – For authentication and dynamic test data.
- **Collection-Level Tests** – For status code, response time, and JSON validation.
- **Request-Specific Tests** – For endpoint-specific validations.

---

## Tech Stack
- **Postman** – API testing
- **JavaScript** – For scripting pre-request logic and assertions

- ## API Documentation  
[API Docs Link](https://automationexercise.com/api_list)

---

 How to Import & Run
1. Import the Collection
- Download the file: [`my-collection.json`](.[/my-collection.json](https://github.com/a-ndi/postman-api-tests/blob/main/New%20Test%20Collection.postman_collection.json)) 
- Open Postman → **Import** → Select the JSON file.

2. Set Up Environment Variables
- Create an environment in Postman.
- Add variables such as:
  - `baseUrl`
  - `authToken`
  - Any other variables required for the tests.

3. Run the Collection
- Use **Collection Runner** in Postman  

