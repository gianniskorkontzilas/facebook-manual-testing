# Test Scenarios for Facebook Login

## Valid Scenarios

### 1. Login with a valid email address and a valid password
- **Description**: Ensure user can log in with a valid email and password.

### 2. Login with a valid phone number and a valid password
- **Description**: Ensure user can log in with a valid phone number and password.

### 3. Login with different ways of writing phone number
- **Description**: Ensure user can log in with different formats of phone numbers (e.g., +2012345454, 0020124234324, 010124342343).

### 4. Login with a Greek format phone number
- **Description**: Ensure user can log in with a Greek phone number format.

### 5. Login with valid user without verifying email or phone number
- **Description**: Ensure user can log in even if they haven’t verified their email or phone number.

### 6. Login with a valid password after using forgotten password functionality
- **Description**: Ensure user can log in after resetting their password.

### 7. Check show password button
- **Description**: Ensure the "show password" button works and reveals the password.

### 8. Check copy/paste of password
- **Description**: Ensure that the password can be copied and pasted correctly into the password field.

### 9. Validate that after login user is redirected to the NewsFeed page
- **Description**: Ensure user is redirected to the NewsFeed after logging in successfully.

### 10. Login with a deactivated account
- **Description**: Ensure login attempt with a deactivated account shows appropriate error.

---

## Invalid Scenarios

### 1. Login with leaving phone or email field empty
- **Description**: Ensure that login fails when phone number or email field is left empty.

### 2. Login with leaving password field empty
- **Description**: Ensure that login fails when password field is left empty.

### 3. Login with an invalid email (not registered)
- **Description**: Ensure login fails with an email that’s not registered.

### 4. Login with an invalid email (wrong format)
- **Description**: Ensure login fails with an email address in the wrong format.

### 5. Login with an invalid phone number (not registered)
- **Description**: Ensure login fails with a phone number that is not registered.

### 6. Login with an invalid phone number (wrong format)
- **Description**: Ensure login fails with a phone number in the wrong format.

### 7. Login with invalid password with valid email
- **Description**: Ensure login fails when the password is incorrect for a valid email.

### 8. Login with invalid password with valid phone number
- **Description**: Ensure login fails when the password is incorrect for a valid phone number.

### 9. Login with invalid password 3 times
- **Description**: Ensure the account is temporarily locked after 3 unsuccessful login attempts.

### 10. Login with invalid password after being blocked from accessing the app
- **Description**: Ensure user can’t log in if their account has been blocked after multiple failed login attempts.

### 11. Login with providing an old password
- **Description**: Ensure login fails when an old password is used after a password reset.

### 12. Login with an old password after using forgotten password functionality
- **Description**: Ensure login fails when the old password is used after resetting the password.

### 13. Login without internet connection
- **Description**: Ensure login attempt fails when there’s no internet connection.

---

## Redirections to Other Sections

### 1. Validate redirection to forgotten password
- **Description**: Ensure that clicking on "Forgot password" redirects the user to the correct page.

### 2. Validate redirection to Sign up page
- **Description**: Ensure that clicking on "Create new account" redirects to the sign up page.

### 3. Validate redirection to Create a page page
- **Description**: Ensure that clicking on "Create a page" redirects to the page creation page.

---

## Compatibility Testing

### 1. Test using Chrome
- **Description**: Ensure login works on Google Chrome browser.

### 2. Test using Firefox
- **Description**: Ensure login works on Mozilla Firefox browser.

### 3. Test using Edge
- **Description**: Ensure login works on Microsoft Edge browser.

### 4. Test using Safari
- **Description**: Ensure login works on Safari browser.

### 5. Test using Safari on iPhone
- **Description**: Ensure login works on Safari browser on iPhone.

### 6. Test using Chrome on iPhone
- **Description**: Ensure login works on Google Chrome browser on iPhone.

### 7. Test using Chrome on Android
- **Description**: Ensure login works on Google Chrome browser on Android.

### 8. Test using any browser on a tablet
- **Description**: Ensure login works on any browser used on a tablet.
