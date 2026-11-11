# VITA Appointment Reservation System - Requirements

## Project Overview

This project is a reservation system for Hartwick College's VITA tax help program. It will keep appointments in one shared schedule so clients and staff do not accidentally book the same household more than once.

## Functional Requirements (FRs)

| ID | Requirement |
| --- | --- |
| FR-01 | The system shall ask screening questions before a client can book an appointment. |
| FR-02 | The system shall only let clients book if they pass screening. |
| FR-03 | The system shall show available appointment dates, times, and locations. |
| FR-04 | The system shall collect the client's full name, phone number, and ZIP code. |
| FR-05 | The system shall allow staff and scheduling partners to book appointments for clients. |
| FR-06 | The system shall stop bookings when a time slot has 8 reservations. |
| FR-07 | The system shall prevent a household from booking more than one appointment across all locations. |
| FR-08 | The system shall save reservations in one shared schedule. |

## Business Rules (BRs)

| ID | Business Rule |
| --- | --- |
| BR-01 | A client must pass screening before booking. |
| BR-02 | Each household can only have one appointment across all locations. |
| BR-03 | Each appointment lasts one hour. |
| BR-04 | A one-hour time slot can have no more than 8 appointments. |
| BR-05 | Hartwick appointments are Mondays and Tuesdays from 6 p.m. to 8 p.m., with up to 16 appointments per day. |
| BR-06 | Library appointments are Saturdays from 10 a.m. to 3 p.m., with no appointments during lunch from 12 p.m. to 1 p.m. |
| BR-07 | Norwich appointments are on Fridays in February. Utica appointments are on the first Friday in April. |
| BR-08 | Binghamton appointments are on the other Fridays in the operating season before April 15, except Norwich and Utica dates. |
| BR-09 | Library and Friday service days can have up to 32 appointments. |

## Design Diagrams

The `Design Diagrams` folder contains the Use Case Diagram and ERD. The diagrams use the actors, requirements, and scheduling rules above.

These are design requirements for the planned final project, not a claim that the full reservation system is already implemented.
