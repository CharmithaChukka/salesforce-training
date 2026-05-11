# Salesforce Summer Program – Day 3 Data Modeling

## 1. Difference Between App, Object, Record, and Field

### App
An app is a collection of related tabs and objects used for a specific business purpose.

Example:
College Management App

---

### Object
An object is like a database table that stores data.

Examples:
- Student
- Faculty
- Course

---

### Record
A record is a single row of data inside an object.

Example:

| Student Name | Age |
|--------------|-----|
| Ravi Kumar   | 20  |

This complete row is called a record.

---

### Field
A field is a column that stores specific information.

Examples:
- Name
- Email
- Age

---

# 2. Standard vs Custom Objects

## Standard Objects
These are already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

## Custom Objects
These are created by users according to business needs.

Examples:
- Student
- Faculty
- Course
- Department

---

# 3. College Management System Data Model

## Objects Created
- Student
- Faculty
- Course
- Department

---

## Relationships

### Department → Faculty
One department can have many faculty members.

Relationship Type:
Lookup Relationship

---

### Department → Course
One department can offer many courses.

Relationship Type:
Lookup Relationship

---

### Course → Student
One course can have many students.

Relationship Type:
Lookup Relationship

---

## Diagram

```text
Department
   │
   ├── Faculty
   │
   └── Course
           │
           └── Student
```

(Add screenshot/image here if available)

---

# 4. Formula Fields

## Formula Field 1 – Full Name

Formula:
```text
First Name + Last Name
```

Why?
This automatically combines first name and last name and avoids manual typing mistakes.

---

## Formula Field 2 – Remaining Seats

Formula:
```text
Total Seats - Filled Seats
```

Why?
This automatically shows available seats and saves time.

---

## Formula Field 3 – Percentage

Formula:
```text
(Marks Obtained / Total Marks) * 100
```

Why?
This automatically calculates percentage and reduces calculation errors.

---

# 5. Validation Rules

## Validation Rule 1 – Email Cannot Be Empty

Purpose:
Prevents saving student records without email address.

---

## Validation Rule 2 – Student Age Cannot Be Negative

Purpose:
Prevents invalid age values.

---

## Validation Rule 3 – Course Seats Cannot Exceed Limit

Purpose:
Prevents overbooking of students into courses.

---

# 6. Reflection – Why Structured Data Matters

Companies need structured data because it keeps information organized, reduces errors, improves searching, and helps manage large amounts of business data efficiently. Random spreadsheets can become confusing and difficult to maintain when data increases.

---

# Reflective Questions

## 1. Why can’t companies manage everything using Excel sheets?

Excel sheets become difficult to manage when data grows large and multiple people work on it.

---

## 2. Why are relationships important between objects?

Relationships connect related data and help organize information properly.

---

## 3. What problems happen if data is inconsistent?

Inconsistent data causes confusion, wrong reports, and business mistakes.

---

## 4. Why should repetitive calculations be automated?

Automation saves time and reduces human errors.

---

## 5. Why should invalid data be blocked early?

Blocking invalid data improves data quality and prevents future problems.

---

## 6. Why is Salesforce called a metadata-driven platform?

Salesforce is metadata-driven because applications can be customized without changing actual code.
