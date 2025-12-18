# UITesting-automation
Develop automation with a process in Selenium

## Mission requirements:

### 1. Introduction to the tools:
* You must be familiar with the tools chosen to 
    perform the tests (such as: Selenium WebDriver, Python, pytest).
* You must perform a proper installation
    of the tools to set up a workspace in doker .

### 2. Developing automation for basic operations:
* Open automation to open the website's home page.
* Check that the home page loaded successfully
    (make sure the status code is 200).

### 3. Checking the identification of elements in the user interface:
* Make sure all the fields listed in the test script are present.
* Make sure all the buttons listed in the test script are there.

### 4. Data entry and operations:
* Enter valid data for all fields.
* Click the "Submit" button and wait for the page to update accordingly 
    (this may involve moving to a new page or displaying a success message).

### 5. Health checks:
* When the information entered is correct, 
    verify that you receive a success message.
* Check the edge case input
    (all options listed in the test script)
    * Make sure the system displays an appropriate error message.

### 6. End of test:
* Ensure that the process is carried out correctly 
* A report of successes and errors should be issued.
* The code you wrote should be able to run automatically in multiple
    environments (on a local computer, or in a remote environment).

## Tools and framework:
* *Selenium* *WebDriver* with *Python*.
* *pytest* to automatically run the tests.
* *WebDriverWait* or *Explicit Waits* to track page loads.

## Success criteria:
* All functions should be completed using as little
    duplicate code as possible (reusability).
* The Page Object Model should be used to manage UI 
    elements and actions.
* The code must be clear and easy to maintain.

## Additional instructions:
* *Documentation*: 
    Provide brief documentation with instructions on 
    how to run the code and which systems need to be installed.
* *Results*:
    A run report must be submitted detailing the results of 
    all tests (success or failure).