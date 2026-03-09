# Facebook Manual Testing

This repository contains manual testing for Facebook, specifically focusing on the **Signup** and **Login** pages. The project aims to create **Test Scenarios** and **Test Cases** for the mentioned functionalities, utilizing tools such as **Trello** for Test Scenarios and **Google Sheets** for Test Cases.


## Project Description

This repository contains manual testing for two key Facebook functionalities:

- **Signup Page**: User registration page.
- **Login Page**: User login page.

The **Test Scenarios** and **Test Cases** were created to ensure that both pages function correctly under various conditions, including both valid and invalid inputs.

## Test Scenarios

The **Test Scenarios** have been recorded using **Trello**. The main categories of scenarios include:

### Facebook Signup

1. **Valid Scenarios**:
   - Validate sign up with a valid phone number.
   - Validate sign up with a valid email address.
   - Validate providing a short valid first or surname (e.g., "Yu-jk").
   - Validate sign up with valid age in the range of 13 and 18 years old.
   - Validate providing different values for Gender.

2. **Invalid Scenarios**:
   - Validate leaving first name field empty.
   - Verify providing numbers or special characters in first name.
   - Verify providing an email with wrong format.
   - Validate a password with less than 6 digits.
   - Validate providing a date of birth less than 13.

### Facebook Login

1. **Valid Scenarios**:
   - Login with a valid email address and valid password.
   - Login with valid phone number and valid password.
   - Login with different ways of writing phone number.
   - Validate login after using forgotten password functionality.

2. **Invalid Scenarios**:
   - Login with leaving phone or email field empty.
   - Login with invalid email or phone number (not registered).
   - Login with invalid password after being blocked.
   - Login without internet connection.

The **Test Scenarios** are available on **Trello** for reference and management.

## Test Cases

The **Test Cases** were recorded and organized in **Google Sheets**, including all parameters and expected results for each scenario. The main categories include:

- **Valid Test Cases** for all valid inputs.
- **Invalid Test Cases** for cases where the user provides incorrect data.

The **Test Cases** are available in **Excel** and **CSV** formats in the `test-cases` folder of the repository.


The structure of the repository is as follows:

```plaintext
/facebook-manual-testing
    /test-scenarios
        - test-scenarios-signup.md
        - test-scenarios-login.md
    /test-cases
        - test-cases-signup.xlsx
        - test-cases-login.xlsx
    /screenshots
        - facebook-signup-screenshot.png
