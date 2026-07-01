# Warehouse Management System

A commercial-grade Warehouse Management and Accounting System designed for cold storage and commodity warehouses handling products such as **Dry Chilli, Dry Ginger, Tamarind, Turmeric, Maize, and other agricultural commodities**.

The cross-platform application digitizes day-to-day warehouse operations by managing inventory movement, financial accounting, customer transactions, invoicing, and reporting through a unified desktop application.

> **Note:** This repository showcases the architecture, features, and technologies of the project. The complete source code is private because the application is commercially deployed and contains proprietary business logic.

---

# Overview

This application streamlines the complete workflow by providing an integrated platform for inventory management, accounting, reporting, and customer communication.

The software has been successfully deployed for commercial warehouse operations.

---

# Key Features

## Inventory Management

* Commodity-wise stock management
* Deposit (ACK) management
* Withdrawal (DC) management
* Running stock calculation
* Opening and closing stock balances
* Daily stock movement

---

## Accounting

* Ledger Management
* Customer Account Statements
* Invoice Generation
* Running Balance Calculation
* Profit & Loss Statement
* Balance Sheet
* Financial Year Management
* Ledger Reports

---

## Reports

The system provides multiple business reports including:

* Stock Statement
* Commodity-wise Stock Report
* Detailed Stock Report
* Customer Ledger Statement
* Invoice Reports
* Profit & Loss Report
* Balance Sheet
* Warehouse Transaction Reports

---

## WhatsApp Integration

Integrated WhatsApp messaging enables instant sharing of business documents with customers.

Supported documents include:

* ACK Receipt
* Delivery Challan (DC)
* Invoice
* Customer Account Statement
* Stock Statement

This helps warehouse operators communicate with customers quickly without manual document sharing.

---

# Technology Stack

## Backend

* Java
* Spring Boot
* REST APIs
* Hibernate / JPA
* Liquibase

## Frontend

* Angular
* Angular Material
* HTML
* CSS
* TypeScript

## Database

* MySQL

## Desktop Packaging

* Electron
* GraalVM Native Image
* InnoSetup

---

# System Architecture

```text
                +------------------------+
                |     Angular Frontend   |
                +-----------+------------+
                            |
                            | REST APIs
                            |
                +-----------v------------+
                |    Spring Boot API     |
                +-----------+------------+
                            |
               Business Logic & Accounting
                            |
                +-----------v------------+
                |        MySQL           |
                +-----------+------------+
                            |
                Liquibase Database Migration
                            |
                +-----------v------------+
                | Electron Desktop App   |
                +------------------------+
```

---

# Business Modules

* Customer Management
* Commodity Management
* Deposit (ACK)
* Withdrawal (DC)
* Invoice Management
* Ledger Management
* Financial Accounting
* Stock Management
* Reporting
* WhatsApp Integration
* User Authentication
* Desktop Deployment

---

# Highlights

* Commercially deployed business application
* Full-stack architecture using Java and Angular
* Integrated accounting and warehouse operations
* Real-time inventory tracking
* Automated financial reporting
* Desktop application packaging using Electron
* Database version management with Liquibase
* WhatsApp document delivery integration

---

# Screenshots

> Screenshots of the application UI will be added here.

* Login
* <img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/68a663df-3ba8-4932-9db7-6056f089e240" />
* Dashboard
*<img width="1920" height="1030" alt="Capture" src="https://github.com/user-attachments/assets/053f15e0-1475-4fe8-98b6-e00bcdad0dab" />
* Deposit (ACK)
* <img width="1920" height="922" alt="Capture" src="https://github.com/user-attachments/assets/e66f6c91-223d-4331-ba7c-60c969b9889a" />
* Withdrawal (DC)
* <img width="1920" height="918" alt="Capture" src="https://github.com/user-attachments/assets/f655e92c-8a61-4183-bf7b-d8fa03d60908" />
* Invoice
* <img width="1920" height="922" alt="in" src="https://github.com/user-attachments/assets/678eb01b-aa73-416b-9be6-d3aee35b34f9" />
* Stock Reports
* <img width="1920" height="920" alt="detailedstock" src="https://github.com/user-attachments/assets/e366e114-93fa-457c-ab58-f440ab9d57f7" />
* Account Statement
* <img width="1920" height="916" alt="accstmt" src="https://github.com/user-attachments/assets/5b6d23b9-7065-40e2-b2de-b3fc773d2753" />
* Profit & Loss
* <img width="1920" height="920" alt="pl" src="https://github.com/user-attachments/assets/c1cf4050-015a-4ec6-91ac-d8bff6384dbb" />
* Balance Sheet
* <img width="1920" height="918" alt="bs" src="https://github.com/user-attachments/assets/710b6eee-6792-46ce-aa41-ad67852ab2af" />
* Profile
* <img width="1920" height="890" alt="pr" src="https://github.com/user-attachments/assets/05a2f724-f15b-4a4e-aa65-ecc4483f4548" />



---

# Future Enhancements

* To bring Whatsapp Intergration to live(currently running trial version API)
* Multi-warehouse support
  

---

# Disclaimer

This repository is intended to demonstrate the project's architecture, functionality, and technology stack.

The production source code is not publicly available because the software is commercially deployed and contains proprietary business logic.
