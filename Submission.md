# Jest Workshop Submission

## Student Details
- Name: Shorya Taneja
- Roll Number: 2024-B-02112006C
- GitHub Username: shoryataneja

---

## Tests Written

List each test you wrote and briefly explain **what bug or regression it prevents**.

### 1. Test Name: no coupon
**What it protects against:**  
It makes sure the function throws an error when the subtotal is negative, so invalid prices are not accepted.
---

### 2. Test Name: 10% coupon
**What it protects against:**  
It checks that the SAVE10 coupon correctly gives a 10% discount.
---

### 3. Test Name: 50%  boundary case
**What it protects against:**  
It makes sure that when the subtotal is exactly ₹50 and FLAT50 is applied, the final amount becomes zero and does not go negative.
---

### 4. Test Name: Invalid Subtotal Throws Error
**What it protects against:**  
It ensures the function throws an error when the subtotal is not a valid number (like NaN) or is negative.
---

### 5. Test Name: Case-insensitive coupon
**What it protects against:**  
It checks that the coupon works even if the user enters it in lowercase or different letter cases.
---

## CI Pipeline (if implemented)
- Did CI pass successfully? (Yes / No)
- GitHub Actions Run URL:
https://github.com/shoryataneja/jest-workshop/actions
---

## Reflection (1–2 lines)
What is **one thing** you understood better about testing or CI after this workshop?
About how the test cases works in github actions.