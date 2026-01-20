# Registration Test Cases – Demo Web Shop

## TC-REG-001 – Successful Registration
**Preconditions:** User is on the registration page  
**Steps:**
1. Open registration page
2. Select gender
3. Enter valid First Name
4. Enter valid Last Name
5. Enter valid Email
6. Enter valid Password
7. Confirm Password
8. Click Register

**Expected Result:**  
User is successfully registered and redirected to the main page

---

## TC-REG-002 – Registration with Empty First Name
**Preconditions:** User is on the registration page  
**Steps:**
1. Leave First Name empty
2. Fill all other fields with valid data
3. Click Register

**Expected Result:**  
Validation error is displayed for First Name field

---

## TC-REG-003 – Registration with Empty Last Name
**Steps:**
1. Leave Last Name empty
2. Fill other fields with valid data
3. Click Register

**Expected Result:**  
Validation error is displayed for Last Name field

---

## TC-REG-004 – Registration with Invalid Email
**Steps:**
1. Enter invalid email format
2. Fill other fields correctly
3. Click Register

**Expected Result:**  
Validation error is displayed for Email field

---

## TC-REG-005 – Registration with Existing Email
**Steps:**
1. Enter already registered email
2. Fill other fields correctly
3. Click Register

**Expected Result:**  
Error message about existing email is displayed

---

## TC-REG-006 – Password and Confirm Password Mismatch
**Steps:**
1. Enter valid password
2. Enter different confirm password
3. Click Register

**Expected Result:**  
Error message about password mismatch is displayed

---

## TC-REG-007 – Registration with Empty Required Fields
**Steps:**
1. Leave all required fields empty
2. Click Register

**Expected Result:**  
Validation errors are displayed for required fields

---

## TC-REG-008 – Password Masking
**Steps:**
1. Enter password in Password field

**Expected Result:**  
Password characters are masked
