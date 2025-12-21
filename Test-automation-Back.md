```text```
# Test Automation Back.

## Mission Objective:
Developing automated tests for the system's business logic
by testing functions and methods directly, 
without API calls and without dependence on the UI,
to verify calculations, conditions, and business flows.

## 📌 General requirements :
* Tests for functions and classes only
* Development language: Python
* Use in testing framework: pytest / unittest
* No use of API, HTTP, Requests or Selenium
* Unit / Business Logic level testing

## Scope of testing :
Tests should be implemented for:
* Calculation functions (calculations, conditions, formulas)
* Business logic (if / else / loops)
* Exception handling (ValueError, TypeError, custom exceptions)
* Endpoint testing (0, negative values, None, empty strings)
* Type testing (int / float / str / bool)
* State-dependent testing

## Technical Requirements:
* Isolated tests (no dependencies between tests)
* Use Fixtures as needed
* Separation between:
* System code
* Test code
* Test data
* Writing clear assertions
* Readable code with meaningful test names
* Writing for a blog
    * start ans end page
    * start function
    * sucess or error function or page

## 📂 Recommended structure
project/
├── src/
│   ├── calculations.py
│   └── business_rules.py
├── **tests**/
│   ├── **test_calculations.py**
│   └── **test_business_rules.py**
└── **test.log**


## Example of Expectations from a Test
* The function returns a valid value for valid input
* The function throws an exception for invalid input
* The function does not change global state
* The result is consistent for the same input 

## Final product
* Automatic test code for functions
* All tests pass
* Short README:
* How to run tests
* Project structure
* Business assumptions