# YuHome — Short-Stay Property Booking Platform

Technical case study of **YuHome**, a production web platform developed for the presentation and online booking of short-stay properties.

> This repository is a portfolio case study. It does **not** contain the application's source code, credentials, production configuration, customer data or proprietary business rules.

## Project overview

YuHome provides a digital experience for discovering short-stay accommodation, consulting property information and availability, and managing reservations through a centralized web platform.

The project combines a customer-facing booking experience with administrative tools for operational management.

**Live website:** https://yuhome.yucargo.co.ao/pt

## My role

**Full-Stack Developer**

Responsibilities included the implementation and integration of the web application across frontend, backend, database and administrative workflows.

## Problems addressed

The platform was designed to help centralize and digitize processes that would otherwise depend on manual communication and fragmented information, including:

- presenting properties and accommodation information online;
- making availability and booking information easier to access;
- organizing reservation workflows;
- centralizing customer and operational information;
- supporting payment management;
- providing administrative control over the platform;
- offering a responsive experience across desktop and mobile devices;
- supporting both Portuguese and English content.

## Core capabilities

- Property presentation and management
- Property images and descriptive content
- Availability management
- Reservation workflows
- Customer management
- Payment management
- Administrative dashboard
- Operational reporting
- Responsive web interface
- Portuguese and English user experience

## Technology stack

| Layer | Technologies |
| --- | --- |
| Backend | Laravel, PHP |
| Frontend | React, TypeScript, Vite |
| Database | MySQL / MariaDB |
| Authentication | Laravel Sanctum |
| Architecture | Client-server web application with API-based communication |

## Architecture

YuHome follows a modern web application architecture in which the React frontend handles the user experience while Laravel provides application logic, authentication, data access and business workflows.

```text
Users / Administrators
        |
        v
React + TypeScript + Vite
        |
        v
Laravel Application / API
        |
        +---- Authentication (Sanctum)
        |
        +---- Reservation & operational services
        |
        v
MySQL / MariaDB
```

More detail: [Architecture](docs/architecture.md)

## Data model

The production database schema is not published. A simplified conceptual model is documented to demonstrate the application's domain structure without exposing proprietary implementation details.

See: [Database & domain model](docs/database.md)

## Engineering challenges

The project involved more than building static pages. The application had to coordinate property content, availability, reservations, customer information and administrative workflows while keeping the user-facing experience simple and responsive.

See: [Technical challenges](docs/technical-challenges.md)

## Project status

**Production / Live**

The public website is available at:

https://yuhome.yucargo.co.ao/pt

## Development period

The commercial development period is not publicly disclosed in this case study.

## Screenshots

A dedicated directory is prepared for project screenshots:

[View screenshot guidelines](assets/screenshots/README.md)

## Ownership and confidentiality

YuHome is a project developed for **YuHome / YuCargo**. This repository is maintained only as a professional technical case study by the developer.

The source code, credentials, customer information, production infrastructure, internal business rules and other proprietary assets are intentionally excluded.

See: [NOTICE](NOTICE.md)

---

**Developer:** Eugénio Fernandes dos Santos  
**GitHub:** https://github.com/eugeniodossantos
