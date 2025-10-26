# Task 0: Define Entities and Relationships (ER Diagram)

## Objective
Design an Entity-Relationship Diagram (ERD) for the Airbnb Database System.

## Entities
- User
- Property
- Booking
- Payment
- Review
- Message

## Relationships
- A User (host) can own many Properties.
- A User (guest) can make many Bookings.
- A Property can have many Bookings.
- Each Booking has one Payment.
- A User can leave multiple Reviews.
- A Property can have multiple Reviews.
- A User can send messages to other Users (self-referencing).

## Tools
The ER Diagram was created using **Draw.io** and saved as `airbnb_erd.png`.

## Files
- `ERD/requirements.md`
- `ERD/airbnb_erd.png`

