# Data Flow Diagram (DFD) – ALX Airbnb Project

## 📘 Overview
This Data Flow Diagram (DFD) represents how data moves through the ALX Airbnb system. It visually illustrates the processes, data stores, external entities, and data flows that make up the core functionality of the platform.

The system allows users (guests and hosts) to register, manage properties, make bookings, and process payments — just like Airbnb. The DFD helps to understand the data interactions and flow across these operations.

---

## 🧩 Components

### 🧍 External Entities
- **Guest (User):** Registers, books properties, and makes payments.
- **Host:** Lists and manages properties.
- **Admin:** Monitors and manages system data.
- **Payment Gateway:** Handles secure payment transactions.

---

### ⚙️ Processes
1. **User Registration & Authentication** – Handles user sign-up, login, and verification.
2. **Property Management** – Allows hosts to add, edit, or remove property listings.
3. **Booking Management** – Processes property searches, availability, and reservations.
4. **Payment Processing** – Manages guest payments and transactions through the payment gateway.
5. **Review & Feedback** – Enables guests to leave reviews and ratings after stays.
6. **Admin Monitoring & Control** – Provides admin tools to monitor users, bookings, and payments.

---

### 🗃️ Data Stores
- **D1: Users Database**
- **D2: Properties Database**
- **D3: Bookings Database**
- **D4: Payments Database**
- **D5: Reviews Database**

---

### 🔁 Data Flows
- Guest → (1.0) User Registration → D1 (User details)
- Host → (2.0) Property Management → D2 (Property details)
- Guest → (3.0) Booking Management → D3 (Booking records)
- (3.0) → (4.0) Payment Processing → Payment Gateway → D4 (Payment info)
- Guest → (5.0) Review & Feedback → D5 (Review data)
- Admin ↔ (6.0) Admin Monitoring ↔ All Databases

---

## 🧠 Purpose
This DFD helps visualize how the ALX Airbnb system handles data interactions across major modules. It ensures:
- Efficient data flow between processes
- Clear identification of data inputs and outputs
- Enhanced understanding for developers and stakeholders

---

## 📄 File Structure
