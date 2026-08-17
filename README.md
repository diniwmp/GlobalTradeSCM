# 🌍 GlobalTrade SCM

### Enterprise Global Supply Chain Management System

> A modern, secure, modular, and enterprise-grade Supply Chain Management System built with **Jakarta EE / EJB**, designed to automate logistics operations, strengthen security, manage enterprise transactions, and provide reliable real-time supply chain monitoring.

---

## ✨ Overview

**GlobalTrade SCM** is an enterprise Supply Chain Management platform developed as part of the **Business Component Development II** project.

The system modernizes traditional supply chain operations by providing a modular enterprise architecture for managing:

- 🚚 Shipment Tracking
- 📦 Inventory Management
- 🤝 Vendor Management
- 🏭 Warehouse Operations
- 🛃 Customs & Trade Compliance
- 📊 Supply Chain Monitoring
- 🔐 Role-Based Security
- 📝 Audit Logging
- 🔔 Automated Alerts
- ⚡ Exception Handling & Recovery

The application demonstrates advanced Enterprise Java concepts including **EJB Timer Services, Interceptors, Transaction Management, Security, Exception Handling, and modular EAR deployment**.

---

## 🎯 Project Objectives

The main objectives of GlobalTrade SCM are to:

- Automate critical supply chain operations.
- Maintain reliable and consistent logistics transactions.
- Protect sensitive vendor and trade information.
- Provide role-based access control.
- Monitor shipments, inventory, and vendor performance.
- Maintain comprehensive audit trails.
- Improve system resilience through enterprise exception handling.
- Support modular deployment and independent service updates.
- Demonstrate enterprise-level Java development best practices.

---

## 🏗️ Architecture

The system follows a **multi-module Enterprise Java architecture**.

```text
                    ┌──────────────────────────┐
                    │        Web Browser       │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │        SCM Web           │
                    │   JSP / Servlet / UI     │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │        SCM EJB           │
                    │                          │
                    │ Business Services        │
                    │ Timer Services            │
                    │ Interceptors              │
                    │ Transactions              │
                    │ Security                  │
                    │ Exception Handling        │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │       SCM Core           │
                    │                          │
                    │ Entities                 │
                    │ DTOs                     │
                    │ Enums                    │
                    │ Exceptions               │
                    │ Shared Components        │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │       MySQL Database     │
                    │                          │
                    │ Users / Roles             │
                    │ Shipments                 │
                    │ Inventory                 │
                    │ Vendors                   │
                    │ Audit Logs                │
                    └──────────────────────────┘
