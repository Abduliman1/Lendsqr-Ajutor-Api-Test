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
---
## Importing the Postman Collection
1. Open Postman.
2. Click on "Import" in the top-left corner.
3. Select the `Authentication Tests.postman_collection.json` file from the cloned repository folder.
## Running the Tests
1. Open the imported collection in Postman.
2. Set the required environment variables (e.g., base URL, authentication tokens) if needed.
3. Run the collection by clicking on the collection name and selecting "Run Collection."
## Test Cases
The collection includes the following test cases:
1. Valid Login
2. Valid Sign-Up
3. Invalid Login
4. Invalid Sign-Up
5. Missing Email
6. Missing Password
7. Invalid Email
8. Invalid Password
9. Missing Both Email and Password
## Summary of Test Results
### Passed Tests:
- Valid Login
- Valid Sign-Up
### Failed Tests:
- Invalid Login
- Invalid Sign-Up
- Missing Email
- Missing Password
- Invalid Email
- Invalid Password
- Missing Both Email and Password
## Detailed Test Results
### Valid Login
- **Description**: Tests if login is successful with valid credentials.
- **Status**: Passed
### Valid Sign-Up
- **Description**: Tests if sign-up is successful with valid details.
- **Status**: Passed
### Invalid Login
- **Description**: Tests if login fails with invalid credentials.
- **Status**: Failed
### Invalid Sign-Up
- **Description**: Tests if sign-up fails with invalid details.
- **Status**: Failed
### Missing Email
- **Description**: Tests if login fails when the email is missing.
- **Status**: Failed
### Missing Password
- **Description**: Tests if login fails when the password is missing.
- **Status**: Failed
### Invalid Email
- **Description**: Tests if login fails with an invalid email.
- **Status**: Failed
### Invalid Password
- **Description**: Tests if login fails with an invalid password.
- **Status**: Failed
### Missing Both Email and Password
- **Description**: Tests if login fails when both email and password are missing.
- **Status**: Failed
## Notes
The tests were executed successfully, and detailed logs are available in Postman for review. Screenshots and additional logs can be attached if needed.
For any questions or issues, please open an issue in this repository or contact the repository maintainer.
## Steps to Add and Commit the README.md
1. Create the `README.md` file in your repository folder:
   ```sh
   touch README.md
   ```
2. Open the file in a text editor and paste the content provided above.
3. Save the file and add it to your git staging area:
   ```sh
   git add README.md
   ```
4. Commit the new file:
   ```sh
   git commit -m "Add README.md with setup instructions and test results summary"
   ```
5. Push the changes to GitHub:
   ```sh
   git push origin master
   ```
## Verify on GitHub
Go to your GitHub repository and verify that the README.md file has been added and contains the correct information.
## Submission
Include a link to your GitHub repository in your submission document, indicating that the setup instructions, test scripts, and test results summary are all available in the README.md file.
```
### Instructions to Add and Commit the README.md
1. Create the `README.md` file in your repository folder:
   ```sh
   touch README.md
   ```
2. Open the file in a text editor and paste the content provided above.
3. Save the file and add it to your git staging area:
   ```sh
   git add README.md
   ```
4. Commit the new file:
   ```sh
   git commit -m "Add README.md with setup instructions and test results summary"
   ```
5. Push the changes to GitHub:
   ```sh
   git push origin master
   ```
### Verify on GitHub
Go to your GitHub repository and verify that the `README.md` file has been added and contains the correct information.
### Submission
Include a link to your GitHub repository in your submission document, indicating that the setup instructions, test scripts, and test results summary are all available in the `README.md` file.
