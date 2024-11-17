# Hotel1
Hotel system has 3 modules guest, receptionist, and booking
The Hotel Management System is designed to facilitate and streamline the booking and management of hotel rooms. It consists of three primary modules: Room Management, Guest Management, and Booking Management. These modules interact with key actors, such as Guests and Receptionists, to ensure smooth operations within the hotel. 

Actors:
1. Guest: The individual who books and stays in the hotel.
2. Receptionist: The hotel staff responsible for managing bookings and room assignments.

Module and Normal Flow:

1. Room Management Module
Description: This module manages the properties, types, and availability status of hotel rooms.

Actors Involved:
- Receptionist: Checks room availability, assigns rooms to guests, and updates the room's status.
  
Normal Flow:
1. The Receptionist accesses the system to check the status of rooms 
2. If a booking is made, the room's availability status is updated to false.
3. When a guest checks out, the Receptionist updates the room status back to true.

 2. Guest Management Module
Handles the collection and management of guest information such as personal details and contact information.

Actors Involved:
- Guest: Provides their information when making a booking.
- Receptionist: Inputs guest data into the system.

Normal Flow:
1. The Guest shares their name, phone number, and email with the **Receptionist**.
2. The Receptionist inputs this information into the system to create a guest profile.
3. The Guest's profile can be referenced for booking and billing purposes.

3. Booking Management Module
 This module oversees the booking process, linking guest details with room availability and generating booking records.

Actors Involved:
- Guest: Requests to book a room.
- Receptionist: Confirms and creates bookings in the system.

Normal Flow:
1. The Guest requests a room for specific dates.
2. The Receptionist checks available rooms in the Room Management Module.
3. If a room is available, the Receptionist creates a booking record by linking the Guest to the selected Room and specifying the check-in and check-out dates.
4. The system marks the room as `booked` in the Room Management Module.
5. The booking details, including guest and room information, are stored and displayed for confirmation.








