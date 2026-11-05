# Courier Tracking System

**Student Name:** Kundan Kumar  
**ERP:** RU-26-02434  

## Project Description
The Courier Tracking System is a command-line application built in Python 3. It allows a courier office to easily book new parcels, update their delivery status through a strictly defined forward-moving flow, track parcel histories, and search for parcels based on the receiver's name.

## Features
* **Book Parcel:** Add a new parcel to the system with auto-generated unique tracking IDs (e.g., CT1001).
* **Update Status:** Safely update the status of a parcel strictly in the following order: `Booked -> Picked Up -> In Transit -> Out for Delivery -> Delivered`.
* **Track Parcel:** View the complete status history and current details (receiver, destination) of any specific parcel using its Tracking ID.
* **Search by Receiver:** Find all parcels and their current status associated with a specific receiver's name.
* **Validation:** Prevents updating parcels that are already marked as "Delivered" and handles invalid Tracking IDs gracefully.

## Technologies Used
* **Language:** Python 3
* **Concepts:** Dictionaries, Lists, Functions, Data Searching/Validation

## How to Run
1. Ensure you have Python 3 installed on your system.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the project file.
4. Run the application using the following command:
   ```bash
   python courier_tracking.py
   ```

## Project Mentor

*Mentored by:* [Mr. Satyaprakash Sethy](https://github.com/SATYAPRAKASHSETHY)

*GitHub:* [@SATYAPRAKASHSETHY](https://github.com/SATYAPRAKASHSETHY)

*Role:* Python Mentor / Technical Guide 