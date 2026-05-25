## Test Cases - Login Form

---

## TC-01 Successful login
Steps:
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click Login

Expected results:
- User is redirected to /secure
- Success message is dispalyed

---

## TC-02 Invalid Password
Steps:
1. Enter valid username
2. Enter invalid password
3. Click Login

Expected result:
- Error message displayed
- User stays on login page

---

## TC-04 Empty fields
Steps:
1. Leave both fields empty
2. Click Login

Expected result:
- Error message displayed
- Authentication fails

---

## TC-05 XSS Attempt
Steps:
1. Enter <script>alert(1)</script>
2. Enter password
3. Click Login

Expected result:
- Script not executed
- Error message displayed

---

## TC-07 Logout
Steps:
1. Login successfully
2. Click Logout

Expected result:
- User redirected to login page
- Session terminated

---

## TC-08 Access secure page after logout
Steps:
1. Login
2. Logout
3. Enter /secure URL manually

Expected result:
- Access denied
- Redirect to login page
