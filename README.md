# Ship Maintenance Management System (Frontend Simulation)

## Problem

Managing maintenance operations for ships involves tracking multiple entities such as ships, components, and maintenance jobs. Without a structured system, it becomes difficult to monitor job status, assign responsibilities, and ensure timely maintenance.

This project simulates a real-world maintenance management system with structured workflows and role-based operations.

---

## Objective

To design a system that can:

- Manage ships and their components  
- Track maintenance jobs across lifecycle stages  
- Assign responsibilities based on user roles  
- Provide visibility into system performance through dashboards  

---

## System Overview

The system models a simplified enterprise workflow:

- **Ships → Components → Maintenance Jobs**
- Each job moves through states: Created → Assigned → In Progress → Completed
- Users interact based on roles (Admin, Inspector, Engineer)

---

## Key Features

### 1. Role-Based Access Control
- Admin, Inspector, Engineer roles  
- Different levels of interaction and control  

---

### 2. Entity Management
- Ships management (create, update, delete)  
- Components linked to ships  
- Maintenance jobs linked to components  

---

### 3. Workflow Management
- Job lifecycle tracking (status, priority, scheduling)  
- Assignment of engineers to specific jobs  
- Filtering jobs by status, ship, and priority  

---

### 4. Event & Notification System
- Notifications triggered on job updates  
- Helps track system activity and changes  

---

### 5. Dashboard & KPIs
- Total ships  
- Jobs in progress  
- Completed jobs  
- Overdue components  

---

### 6. Calendar View
- Visual scheduling of maintenance jobs  
- Enables tracking of upcoming work  

---

## Key Design Decisions

### 1. Frontend-Only Simulation
Used localStorage to simulate backend persistence and system state.

---

### 2. State Management with Context API
Chose Context API for centralized state handling without introducing unnecessary complexity.

---

### 3. Modular Structure
Separated components, contexts, and utilities to maintain scalability and readability.

---

### 4. Workflow-Oriented Design
Focused on how entities interact rather than just CRUD operations.

---

## What This Project Demonstrates

- Understanding of system design and workflows  
- Ability to model real-world processes in software  
- Frontend architecture and state management  
- Designing structured, scalable applications  

---

## Tech Stack

- React (Hooks, Functional Components)  
- Context API  
- React Router  
- TailwindCSS  
- localStorage  

---

## Limitations

- No backend or real-time updates  
- Data persistence limited to browser storage  
- Simplified role and workflow logic  

---

## Future Improvements

- Add backend with database integration  
- Implement authentication system  
- Real-time job tracking  
- API-based architecture  

---

## Demo

[Add Live Link]
