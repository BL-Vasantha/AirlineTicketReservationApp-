
# ✈️ Airline Ticket Reservation System


✈️ 3. Seat Selection (Optional)

The Seat Selection module allows passengers to view the aircraft seat map and choose their preferred seats before completing the booking. It also supports premium seating, automatic seat assignment, and group seating.

✨ Features
🪑 Seat Map
View the seat layout based on the aircraft.
Show seat availability:
🟩 Available
🟥 Booked
🩶 Blocked
Identify Window, Middle, and Aisle seats.
Highlight Premium and Emergency Exit seats.
✅ Seat Selection
Select preferred seats for each passenger.
Validate seat availability before confirmation.
Apply extra charges for premium seats.
Change seats before payment.
Auto-assign seats if none are selected.
Support adjacent seating for family/group bookings.
Restrict emergency exit seats to eligible passengers.
🔄 Workflow
Select Flight
│
▼
View Seat Map
│
▼
Choose Seat
│
▼
Validate Availability
│
▼
Confirm Selection
│
▼
Proceed to Payment
📌 Business Rules
One passenger can reserve only one seat.
Booked or blocked seats cannot be selected.
Premium seats require additional charges.
Exit row seats are assigned only to eligible passengers.
If no seat is selected, the system assigns one automatically.