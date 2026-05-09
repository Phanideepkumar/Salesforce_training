# Task 2: Platform Understanding

# Introduction

Salesforce is a cloud-based CRM platform used to manage customer relationships, business operations, sales, services, and automation. The platform is built using several important components such as Apps, Objects, and Tabs. These components work together to organize data and improve user productivity.

---

# 1. What is an App in Salesforce?

An App in Salesforce is a collection of related tools, objects, tabs, reports, and dashboards grouped together for a specific business purpose.

Apps help users access all required functionalities from one place.

## Purpose of an App

Apps are used to:
- Organize business processes
- Improve navigation
- Provide centralized access to features
- Separate workflows for different departments

## Examples of Standard Apps

- Sales App
- Service App
- Marketing App

## Example

A company can create an:
### Inventory Management App

This app may contain:
- Products
- Suppliers
- Orders
- Reports
- Dashboards

---

# 2. What is an Object in Salesforce?

An Object in Salesforce is similar to a database table used to store data.

Objects contain:
- Fields (columns)
- Records (rows)

Every business information in Salesforce is stored inside objects.

## Example

### Student Object

| Student ID | Name | Marks |
|---|---|---|
| 101 | Rahul | 90 |
| 102 | Priya | 85 |

Here:
- Student = Object
- Student ID, Name, Marks = Fields
- Each row = Record

---

## Types of Objects

### 1. Standard Objects
Provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity
- Lead

### 2. Custom Objects
Created by users according to business requirements.

Examples:
- Student
- Vendor
- Inventory
- Patient

Custom objects usually end with:
```text
__c
```

Example:
```text
Student__c
```

---

# 3. What is a Tab in Salesforce?

A Tab is a navigation component used to access objects, records, reports, dashboards, or other Salesforce features.

Tabs help users quickly move between different parts of the platform.

## Examples of Tabs

- Accounts Tab
- Contacts Tab
- Opportunities Tab
- Reports Tab

## Purpose of Tabs

Tabs are used to:
- Open objects
- View records
- Navigate the application
- Improve user experience

---

# Relationship Between App, Object, and Tab

```text
App
 ├── Tabs
 │     └── Open Objects
 │            └── Store Records
```

---

# Complete Example

## Sales App

The Sales App may contain:
- Accounts Tab
- Contacts Tab
- Opportunities Tab

Each tab opens a related object.

The objects store:
- Customer data
- Contact details
- Sales opportunities

---

# Key Differences

| Component | Purpose |
|---|---|
| App | Collection of related features |
| Object | Stores business data |
| Tab | Navigation shortcut |

---

# Conclusion

Apps, Objects, and Tabs are fundamental components of Salesforce.

- Apps organize functionalities
- Objects store data
- Tabs help users navigate the platform

Together, they create a structured and efficient CRM system for managing business operations.
