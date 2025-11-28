# Product Management API

A simple RESTful API for managing products — create, read, update, and delete product records from a backend service. This project is intended as a learning/demo backend for product catalogs, inventory, or e-commerce prototypes.

---

## Features

- CRUD operations for products
- JSON-based HTTP API
- Layered structure (routing, controllers, services, data layer)
- Centralized error handling
- Environment-based configuration (port, database URL, etc.)

---

## Tech Stack

- **Runtime:** Node.js
- **Language:** JavaScript
- **Framework:** (commonly Express – adjust if you’re using something else)
- **Database:** Any (e.g. MongoDB / PostgreSQL / in-memory) – wire up in `src/` as needed
- **Package manager:** npm

---

## Getting Started

### 1. Prerequisites

- [Node.js](https://nodejs.org/) (LTS version recommended)
- npm (bundled with Node.js)
- A running database instance if your code uses a real DB

### 2. Clone the repository

```bash
git clone https://github.com/Rai-Samarpan/product-management-api.git
cd product-management-api
