# API testing 

## Description:
Testing API endpoints to ensure they operate according
to technical specifications, return expected responses,
and handle errors correctly.

## Goals
1. Verify that each endpoint returns a correct status code (200, 201, 400, 404, 500, etc.).
2. Verify that the data received conforms to the 
    structure and data type defined in the specification.
3. Check error handling for invalid or missing data.
4. Check permissions and access 
    (if Authentication/Authorization is available).
5. Check performance (Response Time) if applicable.

## Types of tests offered:
* **Functional Testing:** Verify that the API performs the required operation.
* **Negative Testing:** Sending requests with invalid or missing data.
* **Boundary Testing:** Checking input boundaries (min, max, null).
* **Security Testing:** Checking permissions and access, SQL injection, XSS if applicable.
* **Performance Testing:** Measuring response time under load.

## Examples of endpoints to test:
| **Endpoint**    | **Method** | **Expected Status** | **Test Scenario**                         |
| ----------- | ------ | --------------- | -------------------------------------   |
| /users      | GET    | 200             | Getting a list of users                 |
| /users      | POST   | 201             | Create a new user with all required <br>fields  |
| /users/{id} | GET    | 200 / 404       | Accept existing user / non-existent user|
| /login      | POST   | 200 / 401       | Login with correct/incorrect user       |
|             |        |                 | details                                 |

## Expected results:
* API codes and responses conform to the specification.
* Clear and correct error messages when invalid inputs are received.
* No basic security vulnerabilities.

## Suggested tools:
* Postman / Insomnia
* Swagger / OpenAPI
* Automated Testing Framework (Pytest + Requests / RestAssured)