# RaceDay
youtube link
https://youtu.be/9cegsvIe7Hg 
## Project Overview

RaceDay is a web-based event management system designed for the South African running, walking and cycling community.

The system allows organisers to create and manage events, categories and participant results, while participants can browse events, enrol in event categories and view their results.

## User Roles

### Organiser
Organisers can:
- Create, edit and delete events
- Manage event categories
- View event enrolments
- Capture and manage participant results

### Participant
Participants can:
- Create an account and log in
- Browse available events
- View event categories
- Enrol in events
- View their enrolments
- View their personal results

## Project Sections

### Section A – Entity Relationship Diagram

The ERD defines the database structure of the RaceDay system, including the entities, attributes, primary keys, foreign keys and relationships.

The ERD contains 10 main entities:
- Organiser
- Organiser Profile
- Participant
- Participant Profile
- Event
- Category
- Event Category
- Enrollment
- Payment
- Result

The ERD can be found in the `/docs` folder.

Section B – API Endpoint Plan

The API Endpoint Plan defines how the application will communicate with the database.

It includes:
- Authentication
- User profiles
- Events
- Categories
- Event enrolments
- Results
- Role-based access for Organisers and Participants

The API Endpoint Plan can be found in the `/docs` folder.

Section C – SQL Database Script

The RaceDay database is implemented using Microsoft SQL Server.

The SQL script creates:
- The RaceDay database
- All required tables
- Primary keys
- Foreign keys
- Unique constraints
- Check constraints
- Relationships between entities

The SQL script can be found in the `/sql` folder.

## Project Structure

```text
RaceDay/
│
├── docs/
│   ├── ERD.png
│   └── API-Endpoint-Plan.pdf
│
├── sql/
│   └── RaceDay.sql
│
└── README.md
