# Test Scenarios for Facebook Signup

## Valid Scenarios

### 1. Validate sign up with valid phone number
- **Description**: Ensure user can sign up using a valid phone number.

### 2. Validate sign up with valid email address
- **Description**: Ensure user can sign up using a valid email address.

### 3. Validate sign up with Arabic First & Surname
- **Description**: Ensure user can enter Arabic characters for first and surname.

### 4. Validate sign up with Russian First & Surname
- **Description**: Ensure user can enter Russian characters for first and surname.

### 5. Validate providing a short valid first or surname (E.g: "Yu-jk")
- **Description**: Ensure user can provide a short but valid first or surname.

### 6. Validate providing a mobile number with and without country code
- **Description**: Ensure that both formats (e.g., [01234435544, +20123243434, 0020123123213]) are accepted.

### 7. Validate sign up with valid age in the range of 13 and 18 years old
- **Description**: Ensure user can sign up with an age between 13 and 18 years old.

### 8. Validate sign up with valid age in the range of 18 and 120 years old
- **Description**: Ensure user can sign up with an age between 18 and 120 years old.

### 9. Validate providing different values for Gender
- **Description**: Ensure that all gender options are accepted (e.g., Male, Female, Other).
---

## Invalid Scenarios

### 1. Validate leaving first name field empty
- **Description**: Ensure an error message appears if the first name field is left empty.

### 2. Validate leaving surname field empty
- **Description**: Ensure an error message appears if the surname field is left empty.

### 3. Validate leaving email or phone number field empty
- **Description**: Ensure an error message appears if the email or phone number field is left empty.

### 4. Validate leaving password field empty
- **Description**: Ensure an error message appears if the password field is left empty.

### 5. Validate leaving gender field empty
- **Description**: Ensure an error message appears if the gender field is left empty.

### 6. Verify providing numbers or special characters in first name
- **Description**: Ensure user cannot enter numbers or special characters in the first name.

### 7. Verify providing numbers or special characters in surname
- **Description**: Ensure user cannot enter numbers or special characters in the surname.

### 8. Verify providing very short first name ("N")
- **Description**: Ensure that first names with less than 2 characters are not accepted.

### 9. Verify providing very short surname ("N")
- **Description**: Ensure that surnames with less than 2 characters are not accepted.

### 10. Verify providing very long first name (more than 50 characters)
- **Description**: Ensure that first names longer than 50 characters are not accepted.

### 11. Verify providing very long surname (more than 50 characters)
- **Description**: Ensure that surnames longer than 50 characters are not accepted.

### 12. Verify providing a short mobile number ("1234")
- **Description**: Ensure that mobile numbers shorter than 10 digits are not accepted.

### 13. Verify providing a long mobile number (more than 15 digits)
- **Description**: Ensure that mobile numbers longer than 15 digits are not accepted.

### 14. Verify providing a space in the mobile number
- **Description**: Ensure that mobile numbers with spaces are not accepted.

### 15. Verify Copy/Paste mobile number from another website or application
- **Description**: Ensure that the mobile number can be copied and pasted successfully into the input field.

### 16. Verify adding an email with wrong format ("e.g abc342432#")
- **Description**: Ensure that email addresses with invalid characters are rejected.

### 17. Verify adding an email with a mistake in the format ("take@gamil.com")
- **Description**: Ensure that email addresses with incorrect domain names are rejected.

### 18. Validate a password with less than 6 digits (e.g., "A!@#1")
- **Description**: Ensure that passwords with fewer than 6 characters are rejected.

### 19. Validate a password without letters (e.g., "1234!@#")
- **Description**: Ensure that passwords without letters are rejected.

### 20. Validate a password without numbers (e.g., "abcd!@#")
- **Description**: Ensure that passwords without numbers are rejected.

### 21. Validate a password without special characters (e.g., "abcd123")
- **Description**: Ensure that passwords without special characters are rejected.

### 22. Validate providing a date of birth less than 13
- **Description**: Ensure that users under the age of 13 cannot sign up.

### 23. Validate providing a date of birth more than 120
- **Description**: Ensure that users over the age of 120 cannot sign up.
