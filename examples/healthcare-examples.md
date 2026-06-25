# Healthcare Testing Prompt Examples

## Overview

Healthcare applications operate in highly regulated environments where patient safety, privacy, compliance, and data accuracy are critical.

Quality Engineering teams must validate healthcare systems against functional, regulatory, security, and interoperability requirements.

This document demonstrates how prompt engineering can assist healthcare testing activities.

---

# Business Scenario

Electronic Health Record (EHR) Platform

Capabilities:

* Patient Registration
* Appointment Scheduling
* Clinical Records
* Prescription Management
* Billing
* Laboratory Integration

Compliance Requirements:

* HIPAA
* GDPR
* NHS Data Security Standards
* HL7/FHIR Interoperability

---

# Example 1: Requirement Analysis

## Requirement

```text id="3ml6wc"
Only authorized clinicians may access patient medical records.
```

## Prompt

```text id="p6cjlwm"
Act as a Healthcare Quality Engineering Specialist.

Analyze the requirement.

Identify:

- Business Objective
- Compliance Requirements
- Risks
- Test Scenarios
```

## Sample Output

### Compliance Requirements

* HIPAA
* GDPR
* Local Healthcare Regulations

### Risks

* Unauthorized access
* Privacy breaches
* Data exposure

---

# Example 2: Access Control Testing

## Prompt

```text id="bh5xlc"
Generate test scenarios for healthcare role-based access control.

Roles:

- Doctor
- Nurse
- Pharmacist
- Administrator
- Receptionist

Include:

- Positive Tests
- Negative Tests
- Security Tests
```

## Example Scenarios

| Scenario                          | Expected Result |
| --------------------------------- | --------------- |
| Doctor Access                     | Allowed         |
| Nurse Access                      | Limited Access  |
| Receptionist Medical Notes Access | Denied          |
| Invalid Role Access               | Denied          |

---

# Example 3: Synthetic Patient Data Generation

## Prompt

```text id="qj98gj"
Generate synthetic patient test data.

Requirements:

- No real patient information
- Include adults and children
- Include multiple medical conditions

Fields:

- Patient ID
- Age
- Gender
- Diagnosis
- Medication
```

## Benefits

* HIPAA Compliance
* GDPR Compliance
* Reduced Privacy Risk

---

# Example 4: Healthcare API Testing

## Prompt

```text id="65pl8i"
Generate API testing scenarios for FHIR Patient API.

Cover:

- CRUD Operations
- Authentication
- Data Validation
- Interoperability
```

## Sample Scenarios

### Positive

* Create Patient Record
* Update Patient Information

### Negative

* Missing Mandatory Fields
* Invalid Patient Identifier
* Unauthorized Access

---

# Example 5: Defect Analysis

## Defect

```text id="e7hglh"
Patient allergy information not displayed during prescription process.
```

## Prompt

```text id="g7k6kg"
Act as a Healthcare Quality Assurance Consultant.

Analyze the defect.

Provide:

- Patient Safety Impact
- Root Cause Hypothesis
- Risk Assessment
- Corrective Actions
```

## Sample Output

### Impact

High Risk

Potential adverse medication administration.

### Recommended Actions

* Immediate defect fix
* Clinical validation
* Regression testing
* Production monitoring

---

# Example 6: Performance Testing

## Prompt

```text id="4w8o9t"
Generate performance testing scenarios for an Electronic Health Record system.

Consider:

- Concurrent clinicians
- Peak outpatient traffic
- Emergency department workload
```

## Example Metrics

| Metric           | Target      |
| ---------------- | ----------- |
| Login Response   | < 2 seconds |
| Patient Search   | < 3 seconds |
| Record Retrieval | < 5 seconds |
| API Response     | < 1 second  |

---

# Example 7: Compliance Testing

## Prompt

```text id="wlj2ib"
Generate HIPAA compliance test scenarios.

Include:

- Data Privacy
- Access Controls
- Audit Logging
- Encryption
- Data Retention
```

## Sample Compliance Checks

* Encryption validation
* Audit trail verification
* Access authorization review
* Consent management testing

---

# Example 8: Root Cause Analysis

## Incident

```text id="e9pwz9"
Laboratory results delayed by 4 hours.
```

## Prompt

```text id="nws6jd"
Perform root cause analysis.

Step 1:
Review workflow.

Step 2:
Identify integration points.

Step 3:
Identify failure points.

Step 4:
Recommend preventive actions.
```

## Sample Findings

### Root Cause

Message queue bottleneck.

### Corrective Action

Scale integration services.

### Preventive Action

Implement proactive monitoring.

---

# Key Takeaways

Healthcare systems demand:

* High Quality
* High Security
* Regulatory Compliance
* Patient Safety

Prompt engineering can support Quality Engineering teams by accelerating:

* Test Design
* Risk Analysis
* Compliance Validation
* Root Cause Analysis
* Synthetic Data Generation

However, all AI-generated outputs should be reviewed by healthcare subject matter experts before implementation.

