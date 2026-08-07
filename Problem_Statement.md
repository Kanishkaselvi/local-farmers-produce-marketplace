# Problem Statement

## 1. Title
Local Farmers Produce Direct-Selling Marketplace

## 2. Domain
Agriculture / E-Commerce / Marketplace

## 3. Who is the User?

The main users of this application are:

- Farmers who want to sell their agricultural products directly to customers.
- Customers who want to purchase fresh local agricultural products.
- Admin who manages users, products, and marketplace activities.

## 4. What Problem Are We Solving?

Local farmers often depend on intermediaries to sell their agricultural products. This may reduce the profit received by farmers and increase the price paid by customers.

Customers also may not have an easy way to find and purchase fresh agricultural products directly from local farmers.

## 5. Proposed Solution

We propose a web-based marketplace that connects local farmers directly with customers.

Farmers can register, add their agricultural products, set prices, and manage available quantities. Customers can browse, search, and purchase products through the platform.

The system will help farmers reach customers directly and provide customers with easier access to fresh local produce.

## 6. Core Entities / Database Tables

The main database entities are:

1. User
2. FarmerProfile
3. Product
4. Category
5. Cart
6. CartItem
7. Order
8. OrderItem
9. Review

These entities will be connected through meaningful relationships to manage users, products, carts, orders, and reviews.

## 7. User Roles & Permissions

### Farmer
- Register and login
- Manage farmer profile
- Add, update, and delete products
- Manage product quantity and price
- View and manage customer orders

### Customer
- Register and login
- Browse and search products
- View product details
- Add products to cart
- Place orders
- View order status
- Give ratings and reviews

### Admin
- Manage farmers and customers
- Manage products
- Monitor orders
- Manage marketplace activities

## 8. Success Criteria

The project will be considered successful if:

- Farmers can register and securely login.
- Farmers can add and manage agricultural products.
- Customers can browse and search available products.
- Customers can add products to cart and place orders.
- Farmers can view and manage customer orders.
- User roles and permissions are properly implemented.
- The application is deployed and accessible through a public URL.
- The system provides a simple and user-friendly marketplace experience.

## 9. Out of Scope

The following features are outside the initial project scope:

- Physical transportation and delivery management
- Warehouse management
- Large-scale supply chain management
- International sales
- Advanced financial accounting
- Complex logistics management

These features may be considered for future enhancements if required.

## 10. Chosen Track

Java Track

### Technology Stack

- Frontend: React.js
- Backend: Java Spring Boot
- Database: MySQL
- Authentication: JWT
- ORM: Spring Data JPA / Hibernate
- API Documentation: Swagger / OpenAPI
- Testing: JUnit 5
- Version Control: Git and GitHub
- CI/CD: GitHub Actions