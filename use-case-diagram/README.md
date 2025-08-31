# Use Case Diagram: Airbnb Clone Project

## Objective
Visualize system interactions using a **Use Case Diagram** showing the key functionalities like user registration, property booking, payments, and reviews.

---

## Instructions

### 1. Identify Actors
From your backend features, the main actors are:

- **Guest** – Can register, login, search properties, book properties, leave reviews, and make payments.
- **Host** – Can register, login, list properties, update/delete properties, confirm/reject bookings, respond to reviews.
- **Admin** – Can manage users, properties, and bookings (optional, depending on scope).
- **Payment System** – External system for processing payments (Stripe/PayPal).

---

### 2. Identify Use Cases
Key use cases for each actor:

**Guest:**
- Register / Login
- Search Properties
- View Property Details
- Book Property
- Cancel Booking
- Make Payment
- Leave Review

**Host:**
- Register / Login
- Create Property Listing
- Update / Delete Property
- Confirm / Reject Booking
- Respond to Review

**Admin:**
- Manage Users
- Manage Properties
- Manage Bookings

**Payment System:**
- Process Payment
- Refund Payment
