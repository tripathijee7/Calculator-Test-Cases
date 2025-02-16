# Calculator-Test-Cases
# Calculator Test Cases

## Test Case 1: Addition of Two Numbers
**Test Case ID:** TC_ADD_01  
**Test Description:** Verify the addition operation for positive, negative, and decimal numbers.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter two numbers (e.g., `2` and `3`).
2. Perform the addition operation.
3. Check the result.
**Expected Results:** The calculator correctly returns `5.0`.

---

## Test Case 2: Subtraction of Two Numbers
**Test Case ID:** TC_SUB_01  
**Test Description:** Verify the subtraction operation for positive, negative, and decimal numbers.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter two numbers (e.g., `3` and `2`).
2. Perform the subtraction operation.
3. Check the result.
**Expected Results:** The calculator correctly returns `1.0`.

---

## Test Case 3: Multiplication of Two Numbers
**Test Case ID:** TC_MUL_01  
**Test Description:** Verify the multiplication operation for positive, negative, and decimal numbers.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter two numbers (e.g., `2` and `3`).
2. Perform the multiplication operation.
3. Check the result.
**Expected Results:** The calculator correctly returns `6.0`.

---

## Test Case 4: Division of Two Numbers
**Test Case ID:** TC_DIV_01  
**Test Description:** Verify the division operation for positive, negative, and decimal numbers.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter two numbers (e.g., `6` and `3`).
2. Perform the division operation.
3. Check the result.
**Expected Results:** The calculator correctly returns `2.0`.

---

## Test Case 5: Division by Zero
**Test Case ID:** TC_DIV_02  
**Test Description:** Verify that dividing by zero throws an error.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter a number (e.g., `5`) and `0` as the divisor.
2. Perform the division operation.
**Expected Results:** The calculator throws an "ArithmeticException" error with the message `"Division by zero is not allowed"`.

---

## Test Case 6: Non-Numeric Input
**Test Case ID:** TC_INVALID_01  
**Test Description:** Verify that non-numeric input is not accepted.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter a non-numeric value (e.g., `A` and `B`).
2. Try performing an operation.
**Expected Results:** The calculator returns an error indicating invalid input.

---

## Test Case 7: BODMAS Order Verification
**Test Case ID:** TC_BODMAS_01  
**Test Description:** Verify that the calculator follows the BODMAS rule.  
**Preconditions:** Calculator application is running.  
**Test Steps:**
1. Enter the expression `(2 + 3) * 4`.
2. Perform the calculation.
**Expected Results:** The calculator correctly returns `20.0`.

