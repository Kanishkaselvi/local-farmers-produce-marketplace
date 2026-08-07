 Local Farmers Produce Direct-Selling Marketplace

A web-based marketplace that connects local farmers directly with customers to sell fresh agricultural products.

## Overview

This project helps local farmers sell their agricultural products directly to customers. Farmers can add products with price and quantity details, while customers can browse products and place orders.

## Tech Stack

- Frontend: React.js
- Backend: Java Spring Boot
- Database: MySQL
- Authentication: JWT
- ORM: Spring Data JPA / Hibernate
- API Documentation: Swagger / OpenAPI
- Testing: JUnit 5
- Version Control: Git & GitHub

## Architecture Diagram

```mermaid
flowchart TB
    A["Farmer / Customer / Admin"] --> B["React.js Frontend"]
    B --> C["Spring Boot REST API"]
    C --> D["Spring Security + JWT"]
    D --> E["Spring Data JPA / Hibernate"]
    E --> F[("MySQL Database")]
```

## Features

### Farmer
- Register and login
- Add and manage products
- Manage price and quantity
- View customer orders

### Customer
- Register and login
- Browse and search products
- Add products to cart
- Place orders
- Give ratings and reviews

### Admin
- Manage farmers and customers
- Manage products
- Monitor orders

## Project Status

## ER Diagram

```mermaid
erDiagram

    USER ||--o| FARMER_PROFILE : has
    FARMER_PROFILE ||--o{ PRODUCT : sells
    CATEGORY ||--o{ PRODUCT : contains

    USER ||--o| CART : owns
    CART ||--o{ CART_ITEM : contains
    PRODUCT ||--o{ CART_ITEM : added_to

    USER ||--o{ ORDER : places
    ORDER ||--o{ ORDER_ITEM : contains
    PRODUCT ||--o{ ORDER_ITEM : included_in

    USER ||--o{ REVIEW : writes
    PRODUCT ||--o{ REVIEW : receives
```

Currently under development as part of a 60-day Capstone Project.
