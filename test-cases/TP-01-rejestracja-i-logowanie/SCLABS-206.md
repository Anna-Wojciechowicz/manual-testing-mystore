# Test Cases – Registration and Login

## TP-01 – Rejestracja i logowanie

**Application:** My Store  
**Test type:** Manual testing  
**Test scope:** Registration form validation

---

## TC-01: Last name field validation – Negative

**Description:** Verify that the `Last name` field rejects values containing characters other than letters.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- The `First name` field is visible and editable.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Open a web browser | — | The browser opens successfully. |
| 2 | Navigate to the My Store website | My Store URL | The website opens successfully. |
| 3 | Open the sign-in page | Click `Sign in` | The sign-in page opens. |
| 4 | Open the account creation form | Click `No account? Create one here` | The registration form opens. |
| 5 | Validate the `Last name` field | `Kowalska123` | The system rejects the value containing non-letter characters. |

---

## TC-02: Email field validation – Positive

**Description:** Verify that the `Email` field accepts a valid email address that is not already registered.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- The `Email` field is visible and editable.
- The email address is not assigned to an existing account.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Open a web browser | — | The browser opens successfully. |
| 2 | Navigate to the My Store website | My Store URL | The website opens successfully. |
| 3 | Open the sign-in page | Click `Sign in` | The sign-in page opens. |
| 4 | Open the account creation form | Click `No account? Create one here` | The registration form opens. |
| 5 | Validate the `Email` field | `anna.test.2026@example.com` | The system accepts the email address as valid and does not report it as already registered. |

---

## TC-03: Email field validation – Negative

**Description:** Verify that the system rejects an email address that is already registered.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- The `Email` field is visible and editable.
- An account already exists with the email address used in the test.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Open a web browser | — | The browser opens successfully. |
| 2 | Navigate to the My Store website | My Store URL | The website opens successfully. |
| 3 | Open the sign-in page | Click `Sign in` | The sign-in page opens. |
| 4 | Open the account creation form | Click `No account? Create one here` | The registration form opens. |
| 5 | Validate the `Email` field | An email address assigned to an existing account | The system informs the user that the email address is already in use and prevents creating another account with that address. |

---

## TC-04: Email field validation – Missing @ character

**Description:** Verify that the system rejects an email address that does not contain the `@` character.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- The `Email` field is visible and editable.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Open a web browser | — | The browser opens successfully. |
| 2 | Navigate to the My Store website | My Store URL | The website opens successfully. |
| 3 | Open the sign-in page | Click `Sign in` | The sign-in page opens successfully. |
| 4 | Open the account creation form | Click `No account? Create one here` | The registration form opens successfully. |
| 5 | Validate the `Email` field | `annatest2026example.com` | The system rejects the invalid email address and prevents registration from being completed. |

---

## TC-05: Password field validation – Positive

**Description:** Verify that the `Password` field accepts a password containing at least five characters.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- The `Password` field is visible and editable.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Open a web browser | — | The browser opens successfully. |
| 2 | Navigate to the My Store website | My Store URL | The website opens successfully. |
| 3 | Open the sign-in page | Click `Sign in` | The sign-in page opens successfully. |
| 4 | Open the account creation form | Click `No account? Create one here` | The registration form opens successfully. |
| 5 | Validate the `Password` field | `Test123` | The system accepts the password because it contains at least five characters. |

---

## TC-06: Password field validation – Negative

**Description:** Verify that the `Password` field rejects a password shorter than five characters.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- The `Password` field is visible and editable.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Open a web browser | — | The browser opens successfully. |
| 2 | Navigate to the My Store website | My Store URL | The website opens successfully. |
| 3 | Open the sign-in page | Click `Sign in` | The sign-in page opens successfully. |
| 4 | Open the account creation form | Click `No account? Create one here` | The registration form opens successfully. |
| 5 | Validate the `Password` field | `Ab1!` | The system rejects the password because it contains fewer than five characters. |

---

## TC-07: Customer data privacy checkbox – Positive

**Description:** Verify that the `Customer data privacy` checkbox is visible and can be selected and deselected.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Check checkbox visibility | Locate `Customer data privacy` in the registration form | The checkbox is visible. |
| 2 | Select the checkbox | Click the checkbox | The checkbox becomes selected. |
| 3 | Deselect the checkbox | Click the selected checkbox again | The checkbox becomes deselected. |

---

## TC-08: Customer data privacy consent validation – Negative

**Description:** Verify that the system requires the `Customer data privacy` consent during registration.

**Preconditions:**
- User is not logged in.
- My Store website is available.
- The new user registration form is open.
- All other required fields contain valid data.
- The `I agree to the terms and conditions and the privacy policy` checkbox is selected.

**Test steps:**

| Step | Action | Test data | Expected result |
|---|---|---|---|
| 1 | Check checkbox visibility | Locate `Customer data privacy` in the registration form | The checkbox is visible. |
| 2 | Leave the checkbox unselected | Do not select the checkbox | The checkbox remains unselected. |
| 3 | Attempt to create an account without consent | Click `Save` | The system prevents registration from being completed without the required consent. |

---

## TC-09: Customer data privacy checkbox – Negative

**Description:** Verify that the system does not allow registration to be completed without selecting the mandatory `Customer data privacy` consent.

**Preconditions:**
- User is not logged in.
- My Store
