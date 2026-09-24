# Automatic Ticket Classification

## Objective

Automatically classify IT tickets by analyzing keywords in the Short Description.

## Classification Rules

### 1. Wi-Fi Issue

#### Condition

Short Description contains:

- Wi-Fi
- Network

#### Action

Update the record:

Category:

Network

Subcategory:

Wi-Fi

---

### 2. Projector Issue

#### Condition

Short Description contains:

Projector

#### Action

Update the record:

Category:

Hardware

Subcategory:

Projector

---

### 3. Password Issue

#### Condition

Short Description contains:

Forgot password

#### Action

Update the record:

Category:

Access

Subcategory:

Forgot Password

---

### 4. Slow Computer Issue

#### Condition

Short Description contains:

Slow Computer

#### Action

Update the record:

Category:

Performance

Subcategory:

Slow Computer

## Classification Summary

| Short Description Keyword | Category | Subcategory |
|---|---|---|
| Wi-Fi / Network | Network | Wi-Fi |
| Projector | Hardware | Projector |
| Forgot Password | Access | Forgot Password |
| Slow Computer | Performance | Slow Computer |

## Expected Result

When a new ticket is created, the Flow Designer checks the Short Description and automatically updates the Category and Subcategory based on the matching condition.
