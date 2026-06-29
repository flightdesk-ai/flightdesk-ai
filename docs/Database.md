# FlightDesk Platform

# Database Design

Version 0.1

---

# Database Philosophy

The database is designed around real operational objects of a flight school.

Each entity represents a real business object.

The goal is to eliminate duplicated data while maintaining complete operational visibility.

---

# Core Entities

## Users

Represents every authenticated person.

Roles:

* Owner
* Manager
* Chief Flight Instructor
* Instructor
* Student
* Maintenance Engineer

---

## Aircraft

Represents every aircraft operated by the organization.

Contains:

* Registration
* Aircraft Type
* Serial Number
* Status
* Total Time (TT)
* Base Airport

---

## Engine

Represents an aircraft engine.

Each engine has:

* Serial Number
* Type
* Total Time
* TBO
* Installation Date

---

## Propeller

Represents aircraft propeller.

Contains:

* Serial Number
* Type
* Total Time
* TBO

---

## Flight Mission

Represents one scheduled or completed flight.

Contains:

* Aircraft
* Instructor
* Student
* Date
* Departure
* Arrival
* Flight Time
* Status

---

## Booking

Represents reservation of aircraft and instructor.

Contains:

* Aircraft
* Instructor
* Student
* Time Slot
* Status

---

## Maintenance Event

Represents scheduled maintenance.

Contains:

* Aircraft
* Event Type
* Due Hours
* Due Date
* Status

---

## Documents

Represents aircraft documentation.

Examples:

* ARC
* Insurance
* Radio License
* Airworthiness
* Noise Certificate

---

## Notifications

Represents automatic system notifications.

Examples:

* Maintenance Due
* Document Expiration
* Booking Reminder
* Conflict Alert

