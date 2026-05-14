# Salesforce Summer Program – Day 6

## Modules Completed

- Database & .NET Basics
- Apex Triggers

---

# What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce objects. It helps users search, filter, and access records stored in Salesforce databases.

---

# What is an Apex Trigger?

An Apex Trigger is code that runs automatically when data changes in Salesforce. Triggers execute before or after events like insert, update, delete, or undelete.

---

# Difference Between Flow and Trigger

| Flow | Apex Trigger |
|------|------|
| No-code or low-code automation | Code-based automation |
| Easy to build and maintain | Used for complex logic |
| Best for simple business tasks | Best for advanced operations |
| Faster development | More flexible and powerful |

---

# Difference Between Before and After Trigger

| Before Trigger | After Trigger |
|------|------|
| Runs before saving records | Runs after saving records |
| Used for validation and updating values | Used for notifications and related actions |
| Does not require record ID | Record ID is available |

---

# Trigger Use Cases

## 1. Student Registration

Action:
Send welcome email after student registration.

Trigger Event:
When a new student record is created.

---

## 2. Attendance Monitoring

Action:
Send warning message when attendance falls below 75%.

Trigger Event:
When attendance record is updated.

---

## 3. Course Capacity Alert

Action:
Notify faculty when course seats become full.

Trigger Event:
When maximum student limit is reached.

---

## 4. Fee Payment Confirmation

Action:
Send payment confirmation to students.

Trigger Event:
When fee status changes to paid.

---

## 5. Exam Result Notification

Action:
Notify students after exam results are uploaded.

Trigger Event:
When result records are updated.

---

# Flow vs Trigger Thinking

## 1. Simple Email Notification

Recommended:
Flow

Reason:
Easy to create without coding.

---

## 2. Complex Fee Eligibility Check

Recommended:
Apex Trigger

Reason:
Requires complex business logic and validations.

---

## 3. Updating Related Records

Recommended:
Flow

Reason:
Simple automation between related records.

---

## 4. External API Integration

Recommended:
Apex Trigger

Reason:
Requires coding and external system handling.

---

# Query Examples

- Find all students in CSE course.
- Find all courses handled by Faculty Ravi.
- Find students with attendance below 75%.
- Find students who did not pay fees.
- Find all final-year students.
- Find students registered for Java course.
- Find faculty handling more than one course.

---

# Reflection

Enterprise systems need event-driven behavior because actions should happen automatically when data changes. This reduces manual work, improves speed, and provides real-time updates to users and systems.

---

# Reflective Questions

## 1. Why do systems need triggers?

Systems need triggers to automate actions automatically after data changes.

---

## 2. Difference between polling and event-driven systems?

Polling checks repeatedly for updates, while event-driven systems react immediately when events occur.

---

## 3. Why are database queries important?

Queries help retrieve and manage required data efficiently.

---

## 4. When should Flows be preferred over Triggers?

Flows should be preferred for simple automation tasks that do not require complex coding.

---

## 5. What problems happen if automation logic becomes too complex?

Complex automation can reduce performance and make maintenance difficult.

---

## 6. Why should developers think carefully before automating actions?

Poor automation design can create unnecessary operations and system issues.

---

# Key Learnings

- Learned how Salesforce retrieves data using SOQL.
- Understood how Apex Triggers automate actions.
- Learned the difference between Flow and Trigger.
- Understood event-driven architecture concepts.

---

# Screenshot

(Add Trailhead completion screenshots here)

Example:

![Trailhead Screenshot](screenshots/day6-progress.png)
