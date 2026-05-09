# Task 3: Thinking Task

# Introduction

Salesforce provides two main ways to build solutions:

1. Configuration (No Code)
2. Coding using Apex

Salesforce follows the principle:
# “Clicks before Code”

This means developers should first check whether a requirement can be solved using Salesforce configuration tools before writing code.

---

# 1. Configuration (No Code)

Configuration means building features using Salesforce’s built-in tools without programming.

This approach is also called:
- Declarative Development
- Low-Code Development

## Common Configuration Tools

- Flow Builder
- Validation Rules
- Formula Fields
- Process Builder
- Approval Processes
- Page Layouts

---

# When Should We Use Configuration?

Configuration should be used when:
- The requirement is simple
- Salesforce already provides built-in functionality
- Minimal customization is needed
- Faster development is preferred
- Easy maintenance is important

Configuration is usually:
- Faster
- Easier to maintain
- Less complex
- More user-friendly

---

# Example 1: Email Notification

## Requirement
When a new customer record is created, send a welcome email automatically.

## Solution
Use:
- Flow Builder

No coding is required because Salesforce already provides email automation tools.

---

# Example 2: Field Validation

## Requirement
Prevent users from entering negative values in a salary field.

## Solution
Use:
- Validation Rule

Example:
```text
Salary < 0
```

This prevents invalid data without writing Apex code.

---

# 2. Coding (Apex)

Coding is used when business requirements are too complex for standard Salesforce configuration tools.

Salesforce mainly uses:
# Apex

Apex is Salesforce’s backend programming language and is similar to Java.

---

# When Should We Use Coding (Apex)?

Coding should be used when:
- Complex business logic is required
- External system integration is needed
- Advanced automation is required
- High customization is necessary
- Configuration tools are not sufficient

Coding provides:
- More flexibility
- Advanced control
- Custom functionality

---

# Example 1: Payment Gateway Integration

## Requirement
Connect Salesforce with an external payment system to process online payments.

## Solution
Use:
- Apex
- APIs

Reason:
Salesforce configuration tools cannot fully handle external payment processing logic.

---

# Example 2: Complex Business Calculation

## Requirement
Calculate discounts dynamically based on:
- Customer type
- Purchase history
- Seasonal offers
- Product category

## Solution
Use:
- Apex Triggers
- Apex Classes

Reason:
The logic is too complex for simple declarative tools.

---

# Comparison Between Configuration and Coding

| Feature | Configuration | Coding (Apex) |
|---|---|---|
| Development Type | No Code | Programming |
| Complexity | Simple to Medium | Medium to Complex |
| Speed | Faster | Slower |
| Maintenance | Easier | More Technical |
| Flexibility | Limited | High |
| Best For | Standard features | Custom requirements |

---

# Conclusion

Salesforce provides both:
- Declarative tools for simple business requirements
- Apex programming for advanced custom solutions

The recommended Salesforce approach is:

```text
Use Configuration first.
Use Coding only when necessary.
```

This helps reduce complexity and improves maintainability of Salesforce applications.
