# API Testing Prompts

## Objective

Leverage AI to generate comprehensive API test scenarios, validation rules, and automation-ready test cases.

---

## Prompt 1: REST API Test Case Generation

```text
Act as a Senior API Test Architect.

Analyze the following API specification and generate comprehensive test cases.

Include:

- Functional Test Cases
- Positive Scenarios
- Negative Scenarios
- Boundary Value Tests
- Error Handling Tests
- Security Validation
- Data Validation
- Status Code Validation

API Specification:

[Paste API Details]
```

### Expected Output

* Test Case ID
* Request
* Expected Response
* Validation Rules
* Priority

---

## Prompt 2: OpenAPI / Swagger Analysis

```text
Act as an API Quality Engineering Specialist.

Review the following OpenAPI specification.

Generate:

- Functional Test Scenarios
- Missing Validation Rules
- Edge Cases
- Security Risks
- Data Integrity Checks

Specification:

[Paste Swagger/OpenAPI Specification]
```

---

## Prompt 3: API Regression Suite Creation

```text
Generate an API regression test suite.

Cover:

- CRUD Operations
- Authentication
- Authorization
- Error Handling
- Pagination
- Sorting
- Filtering

API Details:

[Paste API Details]
```

---

## Prompt 4: Payment API Testing

```text
Act as a Payments API Testing Expert.

Generate test scenarios for a payment authorization API.

Cover:

- Approved Transactions
- Declined Transactions
- Expired Cards
- Invalid CVV
- Currency Validation
- Duplicate Transactions
- Fraud Scenarios
- Timeout Handling

API Details:

[Paste API Specification]
```

