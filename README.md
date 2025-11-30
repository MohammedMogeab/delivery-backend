# Delivery Backend

A modular Go backend for a multi-tenant delivery management platform.

This service powers a system where:
- **Store owners** create and manage delivery orders.
- **Drivers** accept tasks, track routes, and complete deliveries.
- **Admins** monitor the platform, approve drivers, and manage rewards.
- The system handles **live tracking, rewards, wallet balances, notifications, chat, and support tickets**.

## Tech Stack

- **Language:** Go
- **Architecture:** Modular monolith (clean-ish layering: domain, repository, service, transport)
- **HTTP Framework:** Gin
- **Database:** MPostgreSQL (via `database/sql`  ORM )
- **Cache / Realtime:** Redis (planned)
- **Modules:** 
  - Auth & Users
  - Stores & Drivers
  - Orders & Assignment
  - Delivery & Tracking
  - Rewards & Wallet
  - Chat & Notifications
  - Admin & Support

## Project Status

🚧 **Work in progress** – core project structure is ready (modules & folders),
and we are gradually implementing features: authentication, order creation,
driver assignment, delivery tracking, rewards, and more.

## License

This project is licensed under the [MIT License](./LICENSE).
