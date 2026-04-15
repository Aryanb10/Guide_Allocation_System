# Guide Allocation System

## Overview
The Guide Allocation System is a database-driven project designed to manage the allocation of academic guides to students for their projects. It provides a structured approach to store and manage data related to students, faculty guides, and project assignments using a relational database.

## Objectives
- Design an efficient database for project allocation.
- Maintain records of students, guides, and projects.
- Ensure fair distribution of students among guides.
- Minimize manual errors in allocation.

## System Architecture
This project follows a database-centric architecture:

User / Admin interface -> Application backend -> Database

## Database Design

### Entities
- Student
- Guide / Faculty
- Admin
- Project
- Allocation

### Relationships
- One guide supervises multiple students.
- Each student is assigned one guide.
- Each project is associated with a guide.
- The allocation table links students, guides, and projects.

## Features

### Student Management
- Store student details.
- Track assigned guide and project.

### Guide Management
- Store faculty information.
- Define maximum student capacity.

### Project Management
- Maintain project details.
- Associate projects with guides.

### Allocation System
- Assign students to guides and projects.
- Maintain relational integrity using foreign keys.

## Working
1. Insert student and guide records.
2. Add project details.
3. Assign projects to guides.
4. Allocate students using the allocation table.

## Technologies Used
- Frontend: React and Vite
- Backend: Node.js and Express
- Database: SQLite

## Advantages
- Structured data organization.
- Reduces manual effort.
- Ensures data consistency.
- Easy to extend and scale.

## Future Enhancements
- Improve automated allocation algorithms.
- Add reporting and analytics.
- Expand role-based access controls.
