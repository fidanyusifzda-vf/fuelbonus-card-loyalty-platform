# FuelBonus API Documentation

## Overview

This directory contains the REST API documentation for the FuelBonus Card Loyalty Platform.

The API enables secure communication between client applications and backend services responsible for customer management, cashback processing, loyalty tiers, fuel balance, transactions, and fraud monitoring.

---

## Base URL

### Local

```
http://localhost:3000/api
```

### Production

```
https://fuelbonus-backend.onrender.com/api
```

### Swagger

```
https://fuelbonus-backend.onrender.com/api-docs
```

---

## Authentication

The API uses Bearer Token authentication.

Example

```
Authorization: Bearer <access_token>
```

---

## API Modules

### Authentication

- Login
- Token Validation

### Customers

- Get Customers
- Get Customer Details

### Cashback

- Cashback History
- Cashback Balance

### Tier Management

- Tier History
- Tier Upgrade
- Tier Downgrade

### Fuel Balance

- Fuel Balance
- Fuel Redemption

### Transactions

- Transaction History

### Fraud

- Fraud Status
- Risk Monitoring

---

## Response Format

Request

```
application/json
```

Response

```
application/json
```

---

## HTTP Status Codes

| Code | Description |
|------|-------------|
|200|OK|
|400|Bad Request|
|401|Unauthorized|
|403|Forbidden|
|404|Not Found|
|422|Unprocessable Entity|
|429|Too Many Requests|
|500|Internal Server Error|

---

## Documentation Includes

- Authentication
- Endpoint Specifications
- Request Parameters
- Response Examples
- Business Rules
- Validation Rules
- Error Responses
- Acceptance Criteria

---

## Future Improvements

- OpenAPI 3.0 Specification
- Postman Collection
- Sequence Diagrams
- API Versioning
- Rate Limiting
- Webhooks
