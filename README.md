# ISEC - Database Architecture and Administration (AABD) - VendingPLUS Management (2024/2025)

## Context

This repository contains the project materials developed for the practical assignment of the **Database Architecture and Administration (AABD)** course unit, part of the Computer Engineering degree at the Coimbra Institute of Engineering (ISEC), during the 2024/2025 academic year.

## Project Goal

The primary objective was to design and implement a robust relational database and its business logic for the **VendingPLUS** company, which operates vending machines in the Central region of Portugal. The system was designed to optimize the management of logistics and machine maintenance, stock control, and restocking routes.

## Key Aspects Covered

* **Data Modeling:** Creation of the Entity/Relationship (E/R) Model and the Physical Model/Table Diagram for the database structure.
* **DBMS Implementation:** Creation of the database and all tables, indexes, and constraints in **Oracle 11g**.
* **Business Logic (PL/SQL):** Development of **Views**, **Functions**, **Procedures**, and **Triggers** to ensure data integrity and automate critical business processes (e.g., stock management, route planning).
* **Administration and Optimization:** Exception Handling in PL/SQL for robustness, and considerations on Physical Parameter Calculation for performance optimization.
* **Specific Features:**
    * Registration of exclusive sales via digital payment methods (Multibanco, MBWay).
    * Stock management and replenishment logistics with electric vehicles.
    * Alert system for offline or inactive machines.
    * Creation of replenishment routes and travel planning for machines with stock rupture.
    * Development of queries and functions to support management (e.g., best-selling product of the month, distance between machines).

## Tools and Languages Used

* **DBMS:** Oracle 11g
* **Languages:** SQL, PL/SQL
* **Modeling:** Entity/Relationship (E/R) Diagrams

## Repository Contents

* **`Fisico.pdf`**: PDF document containing the database's Physical Model diagram (Table Diagram).
* **`s)_t).pdf`**: Delivery Report detailing the implementation of the assignment's requirements and technical solutions.
* **`202325_AABD_Trabalho_Prático_v01.02.pdf`**: Original assignment brief (for context).
* **SQL Scripts:** SQL files containing the scripts for database creation, views, procedures, functions, and triggers.

## Authors

* Diogo Marques Silva
* Pedro Miguel Duarte Águas
