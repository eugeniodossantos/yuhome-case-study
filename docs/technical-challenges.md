# Technical Challenges

## 1. Connecting the public experience to operational workflows

A booking platform is not only a marketing website. Public-facing property information must remain connected to operational data such as availability, reservations and customer records.

The architecture therefore needed to separate presentation concerns from backend business logic while keeping the experience coherent for users.

## 2. Reservation and availability consistency

Reservation systems need consistent handling of property availability and booking periods.

The application structure centralizes these operations in backend services instead of relying only on frontend state.

## 3. Administrative complexity

The customer experience must remain simple even though the administrative side has to manage several related domains:

- properties;
- reservations;
- customers;
- payments;
- operational information.

This required organizing the application into clear functional areas rather than building a collection of disconnected screens.

## 4. Frontend/backend integration

React and TypeScript provide the interactive client experience, while Laravel handles application logic and persistence.

Clear API boundaries and predictable validation behavior are important to keep the frontend and backend synchronized.

## 5. Authentication and protected operations

Administrative and authenticated functionality must not be exposed to anonymous users.

Laravel Sanctum forms part of the authentication architecture used to protect application access and authenticated communication.

## 6. Responsive experience

Short-stay accommodation users frequently access booking platforms from mobile devices.

The interface therefore needs to preserve clarity, navigation and booking usability across different screen sizes.

## 7. Multilingual presentation

Supporting Portuguese and English requires the interface and content structure to remain coherent across both language experiences rather than treating translation as an afterthought.

## 8. Confidentiality

Because YuHome is a real production project developed for a third party, this public portfolio repository deliberately documents engineering decisions without exposing source code, production configuration, customer data or proprietary implementation details.
