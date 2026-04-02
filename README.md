# TravelPlanner Database System

TravelPlanner is a relational database system developed using SQL to manage and organize travel bookings. The system stores and processes data related to customers, flights, hotels, tours, transport, tour guides, and activities in an integrated and structured way.

---

## Overview
TravelPlanner is designed to support travel planning operations by organizing all booking-related data into a single database system. It allows efficient management of travel services such as flights, hotel reservations, tours, and activities.

The system models real-world relationships between entities and supports complex queries to retrieve and manage data effectively.

---

## Features
- Manage customer information (name, age, gender, email)
- Track flight bookings (price, date, destination)
- Manage hotel reservations (room number, services)
- Organize tours and tour guides
- Manage transportation details
- Store and manage travel activities
- Support complex queries and data analysis

---

## Database Design
The database was designed using:

- **EER Diagram (Enhanced Entity Relationship Model)**
- **Relational Schema**
- **Primary and Foreign Keys**
- **Many-to-Many Relationships (M:N)**

### Key Relationships
- Customers can book multiple flights and hotels
- Tours can include multiple activities
- Tours can be linked to transport and tour guides
- Customers can participate in multiple tours

---

## Main Tables
- Customer  
- Flight  
- Hotel  
- Booking  
- Book (Hotel Booking)  
- Tour  
- Transport  
- Tour_Guide  
- Activities  

---

## SQL Implementation

### DDL (Data Definition Language)
- Create database
- Create tables with constraints (PK, FK)

### DML (Data Manipulation Language)
- Insert records  
- Update records  
- Delete records  

---

## 📊 Queries and Operations

The project includes multiple SQL queries such as:

- Retrieve hotels with specific services (e.g., spa)
- Update flight prices
- Count customers grouped by gender
- Retrieve bookings with total price > 20000
- Find customers based on name patterns
- Calculate average flight price
- Find minimum and maximum booking values

---

## Features

###  Views
A view was created to display customer full name and age for easier data access.

### Trigger
A trigger updates the average tour guide rate automatically when new data is inserted.

### Joins
Join operations were used to combine data from multiple tables (e.g., customer and booking).

### Delete Operations
- Delete records based on conditions (age, ID)
- Remove specific entries from tables

---

##  Technologies Used
- SQL  
- MySQL / MariaDB  
- Database Design (EER & Relational Model)  

---

