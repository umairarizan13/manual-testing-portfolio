# SauceDemo – Shopping Cart Test Cases

**Project:** SauceDemo  
**Module:** Shopping Cart  
**Testing Type:** Functional Testing  
**Website:** https://www.saucedemo.com/

---

## TC001 – Add a product to the cart

**Test Scenario ID:** TS001

**Priority:** High

**Preconditions:**
- User should be logged in.
- Products page should be displayed.

**Test Data:**
- Product: Sauce Labs Backpack

**Test Steps:**

1. Open the SauceDemo website.
2. Log in using valid credentials.
3. Locate the Sauce Labs Backpack product.
4. Click the Add to cart button.
5. Click the shopping cart icon.
6. Verify that the selected product is displayed.

**Expected Result:**
- The product should be successfully added to the shopping cart.
- The correct product name should be displayed.
- The cart badge should display the correct item count.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC002 – Remove a product from the cart

**Test Scenario ID:** TS002

**Priority:** High

**Preconditions:**
- User should be logged in.
- At least one product should be added to the cart.

**Test Data:**
- Product: Sauce Labs Backpack

**Test Steps:**

1. Open the SauceDemo website.
2. Log in using valid credentials.
3. Add the Sauce Labs Backpack to the cart.
4. Click the shopping cart icon.
5. Verify that the product is displayed.
6. Click the Remove button.
7. Verify that the product is removed.

**Expected Result:**
- The selected product should be successfully removed.
- The product should no longer appear in the cart.
- The cart badge should update accordingly.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC003 – Verify product name in the cart

**Test Scenario ID:** TS003

**Priority:** Medium

**Preconditions:**
- User should be logged in.
- Products page should be displayed.

**Test Data:**
- Product: Sauce Labs Backpack

**Test Steps:**

1. Log in to SauceDemo.
2. Locate the Sauce Labs Backpack.
3. Click Add to cart.
4. Open the shopping cart.
5. Verify the displayed product name.

**Expected Result:**
- The correct product name should be displayed in the shopping cart.
- The product name should match the selected product.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC004 – Verify product quantity

**Test Scenario ID:** TS004

**Priority:** High

**Preconditions:**
- User should be logged in.
- Products page should be displayed.

**Test Data:**
- Product: Sauce Labs Backpack
- Expected Quantity: 1

**Test Steps:**

1. Log in to SauceDemo.
2. Locate the Sauce Labs Backpack.
3. Click Add to cart.
4. Open the shopping cart.
5. Verify the quantity displayed for the product.

**Expected Result:**
- The product should be displayed in the cart.
- The quantity should be displayed as 1.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC005 – Verify cart count

**Test Scenario ID:** TS005

**Priority:** Medium

**Preconditions:**
- User should be logged in.
- Products page should be displayed.

**Test Data:**
- Product 1: Sauce Labs Backpack
- Product 2: Sauce Labs Bike Light

**Test Steps:**

1. Log in to SauceDemo.
2. Add Sauce Labs Backpack to the cart.
3. Verify the cart badge displays 1.
4. Add Sauce Labs Bike Light to the cart.
5. Verify the cart badge displays 2.
6. Open the shopping cart.
7. Remove one product.
8. Verify the cart badge updates to 1.

**Expected Result:**
- The cart badge should display the correct number of added products.
- The cart badge should update when a product is removed.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC006 – Continue shopping

**Test Scenario ID:** TS006

**Priority:** Medium

**Preconditions:**
- User should be logged in.
- At least one product should be added to the cart.
- Shopping cart page should be displayed.

**Test Data:**
- Product: Sauce Labs Backpack

**Test Steps:**

1. Log in to SauceDemo.
2. Add Sauce Labs Backpack to the cart.
3. Open the shopping cart.
4. Click the Continue Shopping button.
5. Verify that the products page is displayed.

**Expected Result:**
- User should be redirected to the products page.
- The previously added product should remain in the cart.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC007 – Proceed to checkout

**Test Scenario ID:** TS007

**Priority:** High

**Preconditions:**
- User should be logged in.
- At least one product should be added to the cart.

**Test Data:**
- Product: Sauce Labs Backpack

**Test Steps:**

1. Log in to SauceDemo.
2. Add Sauce Labs Backpack to the cart.
3. Open the shopping cart.
4. Click the Checkout button.
5. Verify that the checkout information page is displayed.

**Expected Result:**
- User should be redirected to the checkout information page.
- The checkout form should be displayed with the required fields.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC008 – Verify product price displayed in the cart

**Test Scenario ID:** TS008

**Priority:** Medium

**Preconditions:**
- User should be logged in.
- Products page should be displayed.

**Test Data:**
- Product: Sauce Labs Backpack

**Test Steps:**

1. Log in to SauceDemo.
2. Locate Sauce Labs Backpack.
3. Note the product price displayed on the products page.
4. Click Add to cart.
5. Open the shopping cart.
6. Verify the product price displayed in the cart.

**Expected Result:**
- The selected product should be displayed in the cart.
- The product price in the cart should match the price displayed on the products page.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## TC009 – Verify empty shopping cart

**Test Scenario ID:** TS009

**Priority:** Medium

**Preconditions:**
- User should be logged in.
- No products should be added to the shopping cart.

**Test Steps:**

1. Open the SauceDemo website.
2. Log in using valid credentials.
3. Make sure no products are added to the cart.
4. Click the shopping cart icon.
5. Verify the shopping cart contents.

**Expected Result:**
- No products should be displayed in the shopping cart.
- The cart should display an empty state.
- The Continue Shopping option should be available.

**Actual Result:** To be updated after execution.

**Status:** Not Executed

---

## Test Case Summary

| Description | Count |
|---|---:|
| Total Test Cases | 9 |
| High Priority | 3 |
| Medium Priority | 6 |
| Not Executed | 9 |

**Note:** Actual results and execution statuses will be updated after performing the test cases on SauceDemo.
