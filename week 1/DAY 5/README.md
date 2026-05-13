# Day 5 – Apex Introduction

## Salesforce Summer Program – Day 5

---

# What is Apex?

Apex is a programming language developed by Salesforce.  
It is used to add custom business logic inside Salesforce applications.

Apex helps developers:
- Automate complex tasks
- Create custom logic
- Integrate external systems
- Perform advanced data processing

Apex works like Java and runs on the Salesforce platform.

---

# Difference Between Flow and Apex

| Flow | Apex |
|---|---|
| No-code/Low-code tool | Programming language |
| Easy to create | Requires coding knowledge |
| Best for simple automation | Best for complex logic |
| Drag-and-drop interface | Written using code |
| Faster development | More flexible and powerful |

---

# Difference Between Configuration and Coding

| Configuration | Coding |
|---|---|
| Uses clicks and setup | Uses programming |
| Easy to maintain | More customization possible |
| Suitable for basic business rules | Suitable for advanced requirements |
| Uses Flow, Validation Rules, Formula Fields | Uses Apex and Triggers |

---

# Real Examples Where Apex Is Needed

## 1. Complex Fee Calculation

A college management system may need different fee calculations based on:
- Scholarship
- Attendance
- Category
- Special discounts

Such complex calculations are difficult using only Flows, so Apex is needed.

---

## 2. External Payment Integration

If the system needs to connect with external payment gateways like:
- Razorpay
- Stripe

Apex is required to send and receive data securely.

---

## 3. Advanced Eligibility Logic

Suppose student eligibility depends on:
- Attendance percentage
- Previous semester marks
- Pending fee status
- Course prerequisites

Handling all these conditions together requires Apex programming.

---

# Integrated College Management System Design

## CRM

The CRM manages the complete student admission and college process.

Example:
- Student inquiries
- Admissions
- Course management
- Notifications

---

# Objects

The system uses different objects such as:
- Student
- Course
- Faculty
- Attendance
- Fee Details

---

# Relationships

Relationships connect objects together.

Example:
- One Student can enroll in many Courses
- One Faculty can teach many Courses

Student ↔ Course relationship helps track enrollments.

---

# Validation Rules

Validation rules ensure correct data entry.

Example:
- Student email must not be empty
- Phone number must contain valid digits

---

# Formula Fields

Formula fields automatically calculate values.

Example:
- Remaining Seats = Total Seats - Filled Seats

---

# Flow Automation

Flows automate business processes.

Example:
- Send automatic notification after successful admission
- Send reminder for fee payment

---

# Apex Usage

Apex is used for:
- Complex admission logic
- Payment integration
- Advanced business rules
- Attendance eligibility processing

---

# Pseudocode Examples

## Example 1

IF seats are full  
THEN block registration

---

## Example 2

IF attendance < 75%  
THEN notify student

---

## Example 3

IF fee not paid  
THEN prevent exam registration

---

## Example 4

IF marks > 90%  
THEN assign scholarship

---

# Reflection

## Why Enterprise Systems Eventually Need Programming

Enterprise systems cannot depend only on clicks and configuration because business requirements become more complex over time.

Flows and configuration tools are useful for simple automation, but advanced business logic, integrations, calculations, and security requirements need programming.

Apex provides:
- Flexibility
- Scalability
- Customization
- Better control over business processes

That is why enterprise applications eventually require programming.

---

# Reflective Questions

## 1. Why is Apex needed if Salesforce already has Flows?

Flows are good for simple automation, but Apex handles advanced and complex business logic.

---

## 2. When should developers prefer no-code solutions?

Developers should prefer no-code solutions for simple and standard business processes because they are faster and easier to maintain.

---

## 3. What problems require custom programming?

Problems involving:
- Complex calculations
- External integrations
- Advanced validations
- Custom workflows

require custom programming.

---

## 4. Why is business logic important in enterprise systems?

Business logic ensures that company rules and processes work correctly inside the system.

---

## 5. Why should developers avoid unnecessary coding?

Unnecessary coding increases maintenance complexity and development time.

---

## 6. How does programming increase flexibility?

Programming allows developers to build custom features and solve complex business requirements efficiently.
