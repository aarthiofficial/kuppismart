# Quote API

A simple RESTful API built with Java Spring Boot that serves random inspirational quotes and applies IP-based rate limiting using Bucket4j.

## Features

- Random inspirational quotes served via `/api/quote`
- IP-based rate limiting (5 requests per minute)
- Swagger UI for API documentation
- Thread-safe handling using ConcurrentHashMap and Bucket4j
- In-memory storage for quotes
- Unit tests for rate limiting

---

## ✅ Setup Instructions

### Prerequisites

- Java 17 or higher
- Maven 3.8.x or higher
- Git

---

### Clone the Repository

```bash
git clone <repository-url>
cd quote-api
