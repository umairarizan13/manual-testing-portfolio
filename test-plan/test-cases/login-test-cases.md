
# SauceDemo – Login Test Cases

**Website:** https://www.saucedemo.com/  
**Module:** Login  
**Testing Type:** Manual Functional Testing

## Test Cases

### TC001 – Login with valid credentials
- Test Data: standard_user / secret_sauce
- Steps:
  1. Open SauceDemo.
  2. Enter a valid username.
  3. Enter a valid password.
  4. Click Login.
- Expected Result: User should successfully access the products page.

### TC002 – Login with incorrect password
- Test Data: standard_user / wrongpassword123
- Steps:
  1. Open SauceDemo.
  2. Enter a valid username.
  3. Enter an incorrect password.
  4. Click Login.
- Expected Result: An error message should appear and login should be rejected.

### TC003 – Login with incorrect username
- Test Data: invalid_user / secret_sauce
- Steps:
  1. Open SauceDemo.
  2. Enter an incorrect username.
  3. Enter a valid password.
  4. Click Login.
- Expected Result: An error message should appear and login should be rejected.

### TC004 – Login with empty username and password
- Test Data: Username: empty / Password: empty
- Steps:
  1. Open SauceDemo.
  2. Leave both fields empty.
  3. Click Login.
- Expected Result: A validation error should appear.

### TC005 – Login with valid username and empty password
- Test Data: standard_user / empty
- Steps:
  1. Open SauceDemo.
  2. Enter a valid username.
  3. Leave the password field empty.
  4. Click Login.
- Expected Result: A validation error should appear.
