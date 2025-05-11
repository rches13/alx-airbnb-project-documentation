# Airbnb Clone Use Case Diagram Documentation

This README provides an overview and instructions for the use case diagram of the Airbnb Clone Backend, designed to visualize the interactions between users and the system for key functionalities.

## Overview
The use case diagram illustrates the relationships between actors (Guest, Host, Admin) and the system's functionalities, focusing on core interactions such as user registration, property booking, and payment processing. It serves as a blueprint for understanding the system's behavior and requirements.

## Diagram Purpose
- Visualize system interactions to identify actors, use cases, and their associations.
- Support development planning by mapping out user-system touchpoints.
- Facilitate communication among stakeholders about system functionality.

## Actors
- **Guest**: Represents users who search for properties, book accommodations, make payments, submit reviews, and receive notifications.
- **Host**: Represents users who manage property listings, respond to reviews, and receive notifications.
- **Admin**: Represents administrators who manage users, approve listings, and monitor payments.

## Use Cases
The diagram includes the following use cases, grouped by functionality:
- **User Management**:
  - Register: Allows new users (Guests and Hosts) to sign up.
  - Login: Enables authenticated access for all users.
  - Manage Profile: Allows users to update their personal details.
- **Property Listings Management**:
  - Add Listing: Enables Hosts to create new property listings.
  - Edit/Delete Listing: Allows Hosts to modify or remove their listings.
- **Search and Filtering**:
  - Search Properties: Allows Guests to find properties based on criteria.
- **Booking Management**:
  - Book Property: Enables Guests to reserve a property.
  - Cancel Booking: Allows Guests to cancel their bookings.
  - View Booking Status: Lets Guests check the status of their bookings.
- **Payment Integration**:
  - Make Payment: Allows Guests to process payments for bookings.
- **Reviews and Ratings**:
  - Submit Review: Enables Guests to provide feedback on their stay.
  - Respond to Review: Allows Hosts to reply to guest reviews.
- **Notifications System**:
  - Receive Notification: Sends updates to Guests and Hosts (e.g., booking confirmations).
- **Admin Dashboard**:
  - Manage Users: Allows Admins to oversee user accounts.
  - Approve Listings: Enables Admins to review and approve new listings.
  - Monitor Payments: Provides Admins with payment transaction oversight.

## Diagram Structure
- The diagram is enclosed within a system boundary labeled "Airbnb Clone System."
- Actors are positioned outside the boundary (Guest and Host on the left, Admin on the right).
- Use cases are represented as ellipses inside the boundary, organized vertically by functionality with clear spacing to avoid overlap.
- Associations are depicted with orthogonal lines connecting actors to their respective use cases.
