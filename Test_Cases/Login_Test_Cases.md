# Login Test Cases – Demo Web Shop

## TC-LOGIN-001 – Successful Login
**Preconditions:**  
User is registered and on the login page

**Steps:**
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Log in

**Expected Result:**  
User is successfully logged in and redirected to the main page

---

## TC-LOGIN-002 – Login with Empty Email
**Steps:**
1. Leave Email field empty
2. Enter valid password
3. Click Log in

**Expected Result:**  
Validation error is displayed for Email field

---

## TC-LOGIN-003 – Login with Empty Password
**Steps:**
1. Enter valid email
2. Leave Password field empty
3. Click Log in

**Expected Result:**  
Validation error is displayed for Password field

---

## TC-LOGIN-004 – Login with Invalid Email Format
**Steps:**
1. Enter invalid email format
2. Enter valid password
3. Click Log in

**Expected Result:**  
Validation error is displayed for Email field

---

## TC-LOGIN-005 – Login with Incorrect Password
**Steps:**
1. Enter valid email
2. Enter incorrect password
3. Click Log in

**Expected Result:**  
Error message about invalid credentials is displayed

---

## TC-LOGIN-006 – Login with Unregistered Email
**Steps:**
1. Enter unregistered email
2. Enter any password
3. Click Log in

**Expected Result:**  
Error message about invalid credentials is displayed

---

## TC-LOGIN-007 – Remember Me Functionality
**Steps:**
1. Enter valid email and password
2. Select "Remember Me" checkbox
3. Click Log in
4. Close and reopen browser

**Expected Result:**  
User remains logged in

---

## TC-LOGIN-008 – Logout Functionality
**Preconditions:**  
User is logged in

**Steps:**
1. Click Log out button

**Expected Result:**  
User is logged out and redirected to the login page
