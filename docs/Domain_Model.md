# FlightDesk Platform

# Domain Model

Version 0.1

---

# Goal

The purpose of this document is to define the business domains of the FlightDesk Platform.

This document is the foundation for system architecture, database design and software development.

---

# Top Level Domain

FlightDesk Platform

The platform consists of seven major business domains.

---

## 1. People

Responsible for every person interacting with the system.

Entities:

* User
* Owner
* Manager
* Chief Flight Instructor
* Instructor
* Student
* Maintenance Engineer

---

## 2. Fleet

Responsible for aircraft and technical assets.

Entities:

* Aircraft
* Engine
* Propeller
* Aircraft Documents
* Aircraft Status

---

## 3. Operations

Responsible for flight operations.

Entities:

* Booking
* Flight Mission
* Flight Log
* Calendar

---

## 4. Maintenance

Responsible for aircraft maintenance.

Entities:

* Maintenance Event
* Inspection
* Component
* Work Order

---

## 5. Training

Responsible for student training.

Entities:

* Training Program
* Lesson
* Exercise
* Progress

---

## 6. Administration

Responsible for organization management.

Entities:

* Flight School
* Airport Base
* Organization Settings
* Reports

---

## 7. AI

Responsible for intelligent services.

Entities:

* AI Assistant
* AI Recommendations
* AI Predictions
* AI Notifications
