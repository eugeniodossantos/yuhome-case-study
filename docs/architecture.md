# Architecture

## Overview

YuHome is structured as a client-server web application with a React-based frontend and a Laravel backend.

The public interface and administrative workflows communicate with backend services responsible for authentication, validation, business logic and persistence.

## High-level architecture

```text
Web Browser
    |
    v
React + TypeScript
Vite
    |
    | HTTP / API communication
    v
Laravel / PHP
    |
    +-- Authentication with Laravel Sanctum
    +-- Property management
    +-- Availability workflows
    +-- Reservation workflows
    +-- Customer management
    +-- Payment management
    +-- Administration and reporting
    |
    v
MySQL / MariaDB
```

## Frontend

The frontend is responsible for:

- responsive user interfaces;
- property and accommodation presentation;
- navigation and booking interactions;
- form handling and validation feedback;
- multilingual presentation;
- communication with backend services.

## Backend

Laravel provides the application layer responsible for:

- request processing;
- authentication and authorization;
- business-rule validation;
- reservation operations;
- data persistence;
- administrative workflows;
- controlled access to application resources.

## Authentication

Laravel Sanctum is used as part of the authentication layer, allowing authenticated application areas to communicate securely with the backend.

## Database

MySQL / MariaDB provides relational persistence for the application's operational data.

The real production schema is intentionally not published. The public documentation contains only a conceptual representation of the domain.

## Deployment

Deployment infrastructure, secrets, server configuration and production environment details are not included in this public repository for security and confidentiality reasons.
