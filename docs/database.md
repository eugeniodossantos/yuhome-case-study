# Database & Domain Model

## Purpose

This document presents a **conceptual** view of the YuHome data domain.

It is not a copy of the production schema and intentionally excludes table names, internal fields, indexes, constraints and proprietary business rules.

## Main domain entities

A simplified representation of the platform can be understood through the following entities:

```text
User
 |
 +---- Customer Profile
 |
 +---- Reservation
          |
          +---- Property
          |
          +---- Availability
          |
          +---- Payment

Property
 |
 +---- Images
 +---- Descriptions / Content
 +---- Availability
 +---- Reservations

Administrator
 |
 +---- Property Management
 +---- Reservation Management
 +---- Customer Management
 +---- Payment Management
 +---- Reporting
```

## Conceptual relationships

### Property

Represents an accommodation unit presented on the platform.

It can be associated with:

- descriptive information;
- images;
- availability periods;
- reservations.

### Customer

Represents a person interacting with reservation processes and customer-facing platform functionality.

### Reservation

Connects a customer to a property for a defined booking period and supports the operational reservation lifecycle.

### Availability

Represents whether a property can be reserved for a specific period.

### Payment

Represents payment-related information associated with reservation workflows.

### Administrative users

Administrative users operate management workflows according to their access level.

## Data protection

No customer data, credentials, production exports, real database dumps or sensitive records are included in this repository.
