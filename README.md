# Manual-Testing-DemoBlaze
**Manual Testing Project – E-commerce Web Application**

**Project Overview**

This project demonstrates structured manual testing conducted on a publicly available e-commerce web application. The objective was to validate core user workflows, identify functional defects, and apply standard QA testing techniques in a real-world scenario.

The project simulates responsibilities of a Junior QA Analyst working within an Agile team environment.

**Testing Objectives**
- Validate critical user journeys (authentication, cart, checkout)
- Identify functional and usability defects
- Apply structured test design techniques
- Produce professional QA documentation
- Demonstrate defect reporting clarity and prioritisation

**Scope of Testing**
- Functional Areas Covered
- User Registration
- User Login & Logout
- Product Browsing
- Add to Cart
- Cart Management
- Checkout Process (Order Placement)
- Form Validation

**Types of Testing Performed**
- Functional Testing
- Regression Testing
- Exploratory Testing
- Negative Testing
- Usability Observations

**Test Design Techniques Applied**
- Equivalence Partitioning
- Boundary Value Analysis
- Positive and Negative Test Scenarios
- Error Guessing

These techniques were applied to ensure meaningful coverage rather than random testing.

**Test Deliverables**
- This repository includes:
- Test Plan
- Test Scenarios
- Detailed Test Cases
- Defect Report
- Test Execution Summary
- Supporting Screenshots

**Test Execution Summary**
- **Metric & Counts:**
- Total Test Cases Executed-25
- Passed-21
- Failed-3
- Blocked-1
- Critical Defects-1
- Major Defects-2
  
**Sample Defects Identified**

-**DEF-001 – Critical**
Checkout process allows order submission with empty mandatory fields.

**Business Impact:**
Potential invalid transaction records and data integrity issues.

**-DEF-002 – Major**
Login failure message lacks clarity when incorrect credentials are entered.

**Business Impact:**
Poor user experience and potential user confusion.

**-DEF-003 – Major**
Cart items do not persist after page refresh.

**Business Impact:**
User frustration and possible loss of conversion.

**Testing Environment**
- OS: Windows 10
- Browser: Google Chrome
- Test Type: Manual Black-Box Testing

**Key Learnings**
- Importance of boundary testing for input validation
- Business risk associated with weak validation controls
- Value of structured defect reporting
- Necessity of regression validation after issue resolution
- Future Enhancements
- Expand coverage with cross-browser testing
- Introduce API-level validation
- Convert manual regression scenarios into automated test scripts
- Integrate testing into CI/CD pipeline

**About This Project**

This project was created as part of a structured self-learning journey toward becoming a Software Tester / QA Analyst. It reflects foundational understanding of testing principles, documentation standards, and defect lifecycle management.
