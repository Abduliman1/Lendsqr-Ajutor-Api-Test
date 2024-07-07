# API Test Scripts

This repository contains Postman test scripts for verifying the functionality of API authentication endpoints. The tests include both positive and negative test cases for login and sign-up functionalities.

## Repository Contents

- `Authentication Tests.postman_collection.json`: The Postman collection containing all the API test scripts.
- `test-results-summary.md`: Summary of the test results, indicating which tests passed and which failed.

## Setup

### Prerequisites

1. **Postman:** If you don't have Postman installed, download and install it from [Postman](https://www.postman.com/downloads/).

### Cloning the Repository

Clone this repository to your local machine using the following command:

```sh
git clone https://github.com/your-username/api-test-scripts.git
cd api-test-scripts

# Importing the Postman Collection
Open Postman.
Click on "Import" in the top-left corner.
Select the Authentication Tests.postman_collection.json file from the cloned repository folder.
Running the Tests
Open the imported collection in Postman.
Set the required environment variables (e.g., base URL, authentication tokens) if needed.
Run the collection by clicking on the collection name and selecting "Run Collection."
Test Cases
The collection includes the following test cases:

Valid Login
Valid Sign-Up
Invalid Login
Invalid Sign-Up
Missing Email
Missing Password
Invalid Email
Invalid Password
Missing Both Email and Password
Summary of Test Results
Passed Tests:

Valid Login
Valid Sign-Up
Failed Tests:

Invalid Login
Invalid Sign-Up
Missing Email
Missing Password
Invalid Email
Invalid Password
Missing Both Email and Password
Detailed Test Results
The detailed results of each test case are documented below:

Valid Login
Description: Tests if login is successful with valid credentials.
Status: Passed
Valid Sign-Up
Description: Tests if sign-up is successful with valid details.
Status: Passed
Invalid Login
Description: Tests if login fails with invalid credentials.
Status: Failed
Invalid Sign-Up
Description: Tests if sign-up fails with invalid details.
Status: Failed
Missing Email
Description: Tests if login fails when the email is missing.
Status: Failed
Missing Password
Description: Tests if login fails when the password is missing.
Status: Failed
Invalid Email
Description: Tests if login fails with an invalid email.
Status: Failed
Invalid Password
Description: Tests if login fails with an invalid password.
Status: Failed
Missing Both Email and Password
Description: Tests if login fails when both email and password are missing.
Status: Failed
Notes
The tests were executed successfully, and detailed logs are available in Postman for review. Screenshots and additional logs can be attached if needed.

For any questions or issues, please open an issue in this repository or contact the repository maintainer.