# VITA Appointment Reservation System

## 1. Project Overview

This project is about making an appointment system for Hartwick College's free tax help program. Right now, people can book appointments through different places, which can cause scheduling problems. The goal is to make one system where clients and staff can easily schedule appointments without confusion.

## 2. Sources Consulted

- VITA Appointment Reservation System project instructions provided in class.
- IRS website: https://www.irs.gov/individuals/free-tax-return-preparation-for-qualifying-taxpayers (accessed November 3, 2026).

## 3. Functional Requirements

| ID | Requirement |
| --- | --- |
| FR-01 | The system shall ask screening questions before a client can book an appointment. |
| FR-02 | The system shall only let clients book if they pass screening. |
| FR-03 | The system shall show available appointment dates, times, and locations. |
| FR-04 | The system shall ask for the client's full name, phone number, and ZIP code. |
| FR-05 | The system shall allow staff and scheduling partners to book appointments for clients. |
| FR-06 | The system shall stop bookings when an appointment time has 8 reservations. |
| FR-07 | The system shall prevent households from booking more than one appointment across the program. |
| FR-08 | The system shall save appointments in one shared schedule. |

## 4. Business Rules

| ID | Rule |
| --- | --- |
| BR-01 | clients must pass screening before booking an appointment. |
| BR-02 | each household can only make one appointment across all locations. |
| BR-03 | each appointment lasts one hour. |
| BR-04 | each one-hour time slot can have up to 8 appointments. |
| BR-05 | Hartwick appointments are Mondays and Tuesdays from 6 p.m. to 8 p.m., with 16 appointments per day. |
| BR-06 | library appointments are on Saturdays from 10 a.m. to 3 p.m., with a lunch break from 12 p.m. to 1 p.m. |
| BR-07 | Norwich appointments are on Fridays in February, and Utica appointments are on the first Friday in April. |
| BR-08 | Binghamton appointments are on other Fridays during the operating season before April 15, except for Norwich and Utica dates. |
| BR-09 | library and Friday service days can have up to 32 appointments. |

## 5. Lab 13 Design Documents

- [Updated requirements](requirement.md)
- [Use Case Diagram](Design%20Diagrams/Use%20Case%20Diagram.svg) ([editable draw.io](Design%20Diagrams/Use%20Case%20Diagram.drawio))
- [ERD](Design%20Diagrams/ERD.svg) ([editable draw.io](Design%20Diagrams/ERD.drawio))

These are the planned requirements and diagrams for the final project. The full reservation system has not been built yet.
