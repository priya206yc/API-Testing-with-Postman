This repository contains dummy API Testing examples created using Postman, covering functional testing, positive and negative scenarios, chaining requests, environment variables, and automated execution using Newman.
It is designed as a QA portfolio project to demonstrate skills in API testing and automation.
This project includes Postman Collections for testing a sample User API.
The tests include:
✔ GET, POST, PUT, DELETE requests
✔ Validations using Postman Tests (JavaScript)
✔ Authentication testing
✔ Response and schema validation
✔ Negative test cases
✔ Data-driven testing (using environment variables)
✔ Test execution with Newman (CLI automation).


API-Testing-Postman/
│
├── PostmanCollections/
│   ├── UserAPIs.postman_collection.json
│   ├── AuthAPIs.postman_collection.json
│
├── Environments/
│   ├── QA.postman_environment.json
│   ├── DEV.postman_environment.json
│
├── SampleData/
│   ├── create_user_payload.json
│   ├── update_user_payload.json
│
├── TestScenarios/
│   └── UserAPI_TestCases.xlsx
│
├── Reports/
│   └── newman-report.html
│
├── Screenshots/
│   ├── CollectionRunSummary.png
│   ├── PassedTests.png
│
└── README.md


JSONPlaceholder (Dummy REST API)

POST → https://jsonplaceholder.typicode.com/posts
PUT → https://jsonplaceholder.typicode.com/posts/1
GET → https://jsonplaceholder.typicode.com/posts

Sample JSON Bodies
POST – Create User 
{
  "name": "Priya Yadav",
  "email": "priya@example.com",
  "phone": "9205080566",
  "username": "priya206",
  "password": "Test@123",
  "role": "QA Engineer"
}

PUT – Update User
{
  "email": "priya.updated@example.com",
  "role": "Senior QA Engineer",
  "status": "active"
}






