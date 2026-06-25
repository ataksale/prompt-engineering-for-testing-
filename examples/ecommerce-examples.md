# E-Commerce Testing Prompt Examples

## Overview

E-commerce platforms are among the most complex digital systems, involving customer journeys, product catalogs, inventory management, payments, promotions, shipping, and returns.

Generative AI can help Quality Engineering teams accelerate testing activities across the entire e-commerce lifecycle.

This document provides practical prompt engineering examples for common e-commerce testing scenarios.

---

# Business Scenario

An online retailer provides:

* User Registration
* Product Search
* Shopping Cart
* Checkout
* Payment Processing
* Order Management
* Returns and Refunds

---

# Example 1: Requirement Analysis

## Requirement

```text id="3l9y2h"
Customers can apply promotional coupon codes during checkout.
```

## Prompt

```text id="nvn1u0"
Act as a Senior QA Architect.

Analyze the following requirement.

Step 1:
Identify business objectives.

Step 2:
Identify functional requirements.

Step 3:
Identify assumptions.

Step 4:
Identify risks.

Step 5:
Generate acceptance criteria.

Requirement:

Customers can apply promotional coupon codes during checkout.
```

## Expected Output

### Business Objective

Increase sales through promotional campaigns.

### Risks

* Invalid coupon application
* Expired coupons
* Duplicate usage
* Discount calculation errors

### Acceptance Criteria

* Valid coupon applies discount.
* Expired coupon rejected.
* Discount displayed before payment.
* Final order amount updated correctly.

---

# Example 2: Test Case Generation

## Prompt

```text id="zvz8k8"
Act as an ISTQB-certified Test Lead.

Generate comprehensive test cases for shopping cart functionality.

Include:

- Positive Scenarios
- Negative Scenarios
- Boundary Conditions
- Error Handling
```

## Sample Output

| Test ID | Scenario               | Expected Result             |
| ------- | ---------------------- | --------------------------- |
| TC001   | Add Product            | Product added successfully  |
| TC002   | Remove Product         | Product removed             |
| TC003   | Maximum Quantity       | Validation triggered        |
| TC004   | Out of Stock Item      | Error message displayed     |
| TC005   | Concurrent Cart Update | Cart synchronized correctly |

---

# Example 3: Test Data Generation

## Prompt

```text id="syab2p"
Generate synthetic e-commerce customer data.

Requirements:

- 50 customers
- GDPR compliant
- Include positive and negative test data

Fields:

- Customer Name
- Email
- Address
- Phone Number
```

## Sample Output

| Customer Type          | Purpose              |
| ---------------------- | -------------------- |
| Standard Customer      | Positive Testing     |
| VIP Customer           | Loyalty Testing      |
| Invalid Email Customer | Negative Testing     |
| International Customer | Localization Testing |

---

# Example 4: Payment Testing

## Prompt

```text id="nlrr7j"
Act as an E-Commerce Payments Specialist.

Generate checkout and payment test scenarios.

Cover:

- Credit Card
- Debit Card
- Digital Wallet
- Failed Payment
- Duplicate Payment
- Refund Processing
```

## Sample Scenarios

### Positive

* Successful Visa payment
* Successful Mastercard payment
* Successful PayPal payment

### Negative

* Expired card
* Invalid CVV
* Insufficient funds
* Network timeout

---

# Example 5: Defect Analysis

## Defect

```text id="p5lzaf"
Discount applied twice during checkout.
```

## Prompt

```text id="w1yjlwm"
Act as a Senior Quality Engineer.

Analyze the following defect.

Provide:

- Root Cause Hypothesis
- Business Impact
- Recommended Investigation Areas
```

## Sample Analysis

### Possible Causes

* Coupon validation service issue
* Duplicate API invocation
* Incorrect discount calculation logic

### Business Impact

* Revenue leakage
* Customer dissatisfaction
* Reconciliation discrepancies

---

# Example 6: Performance Testing

## Prompt

```text id="3w0msp"
Generate performance testing scenarios for Black Friday sales.

Consider:

- 100,000 concurrent users
- Product browsing
- Checkout transactions
- Payment processing
```

## Sample Workload

| Activity        | Percentage |
| --------------- | ---------- |
| Product Search  | 40%        |
| Browse Products | 30%        |
| Add to Cart     | 15%        |
| Checkout        | 10%        |
| Payment         | 5%         |

---

# Example 7: Security Testing

## Prompt

```text id="es7iym"
Generate security test cases for e-commerce checkout.

Cover:

- Authentication
- Authorization
- Payment Security
- Session Management
- Input Validation
```

## Example Security Scenarios

* SQL Injection
* Cross-Site Scripting (XSS)
* Session Hijacking
* Price Manipulation
* Coupon Abuse

---

# Key Takeaways

E-commerce platforms require testing across:

* Functional Quality
* Security
* Performance
* Usability
* Payments
* Data Integrity

Prompt engineering can accelerate test design while improving test coverage and consistency.

