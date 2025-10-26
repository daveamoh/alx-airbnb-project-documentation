# Airbnb Clone — User Stories

This document translates the use case diagram interactions into actionable user stories for the Airbnb Clone backend system. Each story is written from the perspective of the primary actors — Guests, Hosts, and Admins.

---

## 🧍 Guest User Stories

### 1. Account Registration
**As a guest**, I want to be able to register for an account so that I can book and review properties on the platform.

### 2. Search and Book Property
**As a guest**, I want to search for properties by location, price, and amenities so that I can find the best place to stay.  
**As a guest**, I want to book a property for specific dates so that I can confirm my stay securely.

### 3. Make Payment
**As a guest**, I want to make secure payments through supported methods (PayPal, Stripe, Credit Card) so that my booking is confirmed immediately.

### 4. Manage Bookings
**As a guest**, I want to be able to view and cancel my bookings so that I can manage my travel plans easily.

### 5. Review Experience
**As a guest**, I want to leave a review and rating for the property I stayed in so that I can share feedback with the host and other users.

---

## 🏠 Host User Stories

### 6. Manage Property Listings
**As a host**, I want to add, edit, or delete my property listings so that I can control the availability and accuracy of my properties.

### 7. Manage Bookings
**As a host**, I want to view and manage all bookings made for my properties so that I can accept or decline them as needed.

### 8. Receive Payments
**As a host**, I want to receive automatic payouts after a successful booking so that I can earn revenue from my listings.

### 9. Respond to Reviews
**As a host**, I want to respond to guest reviews so that I can maintain a good reputation and improve guest relationships.

---

## 👨‍💼 Admin User Stories

### 10. Manage Platform Data
**As an admin**, I want to manage users, properties, and bookings so that I can maintain platform integrity and compliance.

### 11. Monitor Transactions
**As an admin**, I want to monitor all payments and transactions so that I can ensure financial transparency and resolve disputes.

### 12. Generate Reports
**As an admin**, I want to generate performance and usage reports so that I can analyze system activity and make informed decisions.

---

## 💳 Payment Gateway Interaction

### 13. Process Payments
**As a system**, I want to interact with external payment gateways so that guest payments are securely verified and hosts receive payouts.

---

## 🔔 Notifications

### 14. System Notifications
**As a user**, I want to receive notifications (email or in-app) for booking confirmations, cancellations, and payment updates so that I stay informed about my activities on the platform.

---

### ✅ Summary

| Actor | Example User Stories |
|--------|----------------------|
| Guest | Register, Search, Book, Pay, Review |
| Host | Add Listing, Manage Bookings, Receive Payment |
| Admin | Manage Users, Monitor Payments, Generate Reports |
| System | Process Payments, Send Notifications |

These stories collectively form the foundation for backend API design and feature development in the Airbnb Clone project.
