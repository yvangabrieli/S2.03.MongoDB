# S2.03.MongoDB 

## 📌 Description Nivel 1
This repository contains two MongoDB exercises based on the case study of the optical store **“Óptica Cul d’Ampolla”**.  
Each exercise focuses on designing and managing a NoSQL database to simulate real-world business operations in an optician shop.

### Exercise 1 – Client Interface
The first exercise is developed from the **client’s point of view**.  
It models and queries information related to:
- Customer details, contact data, and registration information.  
- Glasses purchased by each client.  
- Employees responsible for each sale.  
- Referral relationships between clients (clients recommending other clients).  

This structure allows retrieving comprehensive data about clients and their purchase history.

### Exercise 2 – Glasses Interface
The second exercise is developed from the **glasses’ point of view**.  
It focuses on product tracking and supplier relationships, including:
- Brand, model, frame type, colors, and price.  
- Supplier information (address, phone, fax, tax ID).  
- Clients who purchased specific glasses and the employees who handled the sales.  

This perspective enables analysis of product sales and supplier connections.

---

## 💻 Technologies Used
- **MongoDB** – NoSQL database management system.  
- **Docker** – Environment for running MongoDB containers.  
- **Moon Modeler** – For database access and query testing.  

---

## 📋 Requirements
Before starting, make sure you have:
- A working **MongoDB server** (local or Docker container).  
- A MongoDB client such as **Moon Modeler**.  

---

## 🛠️ Installation & Setup
1. Start your MongoDB server or Docker container.  
2. Open Moon Modeler.  
3. Create a new database named **optica** with the following collections:
   - `clients`
   - `employees`
   - `suppliers`
   - `glasses`
   - `sales`
---

## 🧾 Collections Overview

| Collection | Description |
|-------------|-------------|
| **clients** | Stores customer data, contact info, and references to the client who recommended them. |
| **employees** | Contains employees’ names who manage sales. |
| **suppliers** | Holds supplier information including address, phone, fax, and tax ID. |
| **glasses** | Details about glasses (brand, color, type, lenses, price) and their supplier. |
| **sales** | Connects clients, employees, and glasses with the sale date. |

---

## 🎯 Learning Objectives
- Practice database modeling with **documents** and **embedded relationships** in MongoDB.  
- Apply **CRUD operations** (`insert`, `find`, `update`, `delete`).  
- Understand **1:N** and **N:M** relationships using document references.  
- Work with **Docker** and **MongoDB Compass** to manage and query NoSQL data.  

---

## 📁 Deliverable
A single `.js` file containing all MongoDB insert statements,  
with each command written on a single line (code obfuscated as required).

