# How CRM Concepts Fit into Salesforce Platform

# Introduction

Salesforce is mainly a:

# CRM (Customer Relationship Management) Platform

CRM helps companies:

* Manage customers
* Track sales
* Improve communication
* Increase business growth

Salesforce provides CRM features using:

* Objects
* Apps
* Records
* Tabs
* Automation tools

This document explains how important CRM concepts like:

* Account
* Contact
* Opportunity

fit into the Salesforce Platform architecture.

---

# 1. What is CRM?

CRM stands for:

# Customer Relationship Management

It is a system used to:

* Store customer information
* Track customer interactions
* Manage sales processes
* Improve customer relationships

---

# Real-World Example

Suppose a company sells laptops.

The company needs to manage:

* Customers
* Customer contacts
* Sales deals
* Follow-ups
* Orders

Salesforce CRM helps organize all this information.

---

# 2. Salesforce Platform Structure

Salesforce organizes CRM data using:

| Salesforce Component | Purpose                        |
| -------------------- | ------------------------------ |
| Apps                 | Collection of related features |
| Objects              | Database tables                |
| Fields               | Data columns                   |
| Records              | Data rows                      |
| Tabs                 | Navigation shortcuts           |

---

# Basic Salesforce Structure

```text
App
 ├── Objects
 │     ├── Fields
 │     └── Records
 ├── Reports
 └── Dashboards
```

---

# 3. CRM Concepts in Salesforce

The three most important CRM concepts are:

1. Account
2. Contact
3. Opportunity

These are implemented in Salesforce as:

# Standard Objects

---

# 4. Account Object

# What is an Account?

An Account represents:

* A company
* A customer business
* An organization

Example:

* Infosys
* Amazon
* TCS
* Wipro

---

# Account Object in Salesforce

Salesforce provides a built-in standard object called:

# Account

This object stores company-related information.

---

# Example Account Fields

| Field        | Description      |
| ------------ | ---------------- |
| Account Name | Company name     |
| Industry     | Business type    |
| Phone        | Contact number   |
| Website      | Company website  |
| Address      | Company location |

---

# Example Account Record

| Account Name     | Industry    | Phone      |
| ---------------- | ----------- | ---------- |
| ABC Technologies | IT Services | 9999999999 |

---

# Role of Account in CRM

Accounts act as:

# Central Customer Entities

Everything usually connects to accounts.

---

# 5. Contact Object

# What is a Contact?

A Contact represents:

# A person associated with an Account

Example:

* Company manager
* Sales representative
* HR executive

---

# Contact Object in Salesforce

Salesforce provides another standard object called:

# Contact

This stores person-level information.

---

# Example Contact Fields

| Field        | Description     |
| ------------ | --------------- |
| First Name   | Person name     |
| Last Name    | Person surname  |
| Email        | Email address   |
| Phone        | Mobile number   |
| Account Name | Related company |

---

# Example Contact Record

| First Name | Last Name | Email                                     |
| ---------- | --------- | ----------------------------------------- |
| Rahul      | Sharma    | [rahul@gmail.com](mailto:rahul@gmail.com) |

---

# Relationship Between Account and Contact

One Account can have:

# Multiple Contacts

Example:

```text
Account: ABC Technologies
   ├── Rahul Sharma
   ├── Priya Verma
   └── John David
```

This is called:

# One-to-Many Relationship

---

# 6. Opportunity Object

# What is an Opportunity?

An Opportunity represents:

# A potential sales deal

Example:

* Laptop purchase deal
* Software subscription deal
* Service contract

---

# Opportunity Object in Salesforce

Salesforce provides a standard object called:

# Opportunity

This helps track:

* Sales stages
* Revenue
* Probability
* Deal progress

---

# Example Opportunity Fields

| Field            | Description           |
| ---------------- | --------------------- |
| Opportunity Name | Deal name             |
| Amount           | Deal value            |
| Close Date       | Expected closing date |
| Stage            | Deal stage            |
| Account Name     | Related customer      |

---

# Example Opportunity Record

| Opportunity Name  | Amount    | Stage       |
| ----------------- | --------- | ----------- |
| Laptop Bulk Order | ₹5,00,000 | Negotiation |

---

# Opportunity Stages

Typical sales stages:

```text
Lead
  ↓
Qualification
  ↓
Proposal
  ↓
Negotiation
  ↓
Closed Won / Closed Lost
```

---

# Relationship Between CRM Concepts

```text
Account
   ↓
Contact
   ↓
Opportunity
```

---

# Complete Example

## Account

ABC Technologies

## Contacts

* Rahul Sharma
* Priya Verma

## Opportunity

Bulk Laptop Purchase Deal

---

# 7. How CRM Concepts Fit into Salesforce Apps

These CRM objects are grouped inside:

# Salesforce Apps

Example:

# Sales App

---

# Sales App Contains

| Component         | Purpose            |
| ----------------- | ------------------ |
| Accounts Tab      | Customer companies |
| Contacts Tab      | Customer persons   |
| Opportunities Tab | Sales deals        |
| Reports           | Sales analysis     |
| Dashboards        | Business insights  |

---

# Salesforce Navigation Example

```text
Sales App
   ├── Accounts
   ├── Contacts
   ├── Opportunities
   ├── Leads
   ├── Reports
   └── Dashboards
```

---

# 8. How Salesforce Uses Objects Internally

Each CRM concept is stored as:

# An Object

| CRM Concept | Salesforce Object  |
| ----------- | ------------------ |
| Company     | Account Object     |
| Person      | Contact Object     |
| Sales Deal  | Opportunity Object |

---

# Object Structure

Each object contains:

| Component     | Example              |
| ------------- | -------------------- |
| Fields        | Name, Phone, Email   |
| Records       | Actual customer data |
| Relationships | Object connections   |
| Page Layouts  | UI design            |

---

# 9. How the Salesforce Platform Works with CRM Data

---

# Step 1: Create Account

Example:

```text
ABC Technologies
```

Stored in:

# Account Object

---

# Step 2: Add Contacts

Example:

```text
Rahul Sharma
Priya Verma
```

Stored in:

# Contact Object

Linked to:

# Account

---

# Step 3: Create Opportunity

Example:

```text
Bulk Laptop Purchase
```

Stored in:

# Opportunity Object

Linked to:

# Account

---

# Step 4: Track Sales Process

Salesforce tracks:

* Deal progress
* Revenue
* Sales stage
* Closing probability

---

# Complete CRM Flow in Salesforce

```text
Lead
  ↓
Account + Contact
  ↓
Opportunity
  ↓
Closed Deal
```

---

# 10. Why This Structure is Powerful

Salesforce CRM structure helps companies:

* Organize customer data
* Track relationships
* Monitor sales
* Generate reports
* Automate workflows
* Improve business decisions

---

# Example Business Scenario

Suppose a software company receives a new client.

## Account

Tech Solutions Pvt Ltd

## Contact

Ravi Kumar (Manager)

## Opportunity

Software License Purchase

Salesforce connects all this information together.

---

# 11. Benefits of Salesforce CRM Architecture

| Benefit          | Description                      |
| ---------------- | -------------------------------- |
| Centralized Data | All customer data in one place   |
| Easy Tracking    | Track sales and communication    |
| Automation       | Automate workflows               |
| Reporting        | Generate analytics               |
| Scalability      | Handle large business operations |

---

# 12. Key Salesforce Concepts Used

| Concept     | Meaning                      |
| ----------- | ---------------------------- |
| App         | Collection of business tools |
| Object      | Database table               |
| Field       | Data column                  |
| Record      | Data row                     |
| Account     | Company/customer             |
| Contact     | Person related to customer   |
| Opportunity | Sales deal                   |

---

# Final Understanding

The most important idea is:

```text
Salesforce stores CRM concepts as Objects
and organizes them inside Apps.
```

* Account = Customer company
* Contact = Person associated with customer
* Opportunity = Potential sales deal

Together they form the core CRM structure of Salesforce.

---

# Conclusion

Salesforce combines:

* CRM concepts
* Cloud platform architecture
* Objects and apps
* Automation and analytics

to create a powerful
