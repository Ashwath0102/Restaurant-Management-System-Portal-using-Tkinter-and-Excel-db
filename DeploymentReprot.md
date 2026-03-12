# Deployment Report: Restaurant Management System

![Version](https://img.shields.io/badge/Version-2.0--Final-brightgreen)
![Development-Period](https://img.shields.io/badge/Release-May--2020-blue)

This document tracks the iterative development and deployment phases of the Restaurant Management System, from initial login logic to the final feature-complete software.

---

### 🟢 Version 0.1 - 0.4: Foundations & Admin Core
* **v0.1:** Established the Admin login system and secure database for credentials.
* **v0.2:** Designed the initial Admin Menu interface.
* **v0.3:** * Introduced Inventory Management with UI.
    * Added price-altering functionality for inventory items.
    * Integrated inventory tools into the Admin Main Menu.
* **v0.4:** * Connected Inventory Management to the database.
    * Launched the Staff Registration Module (Excel DB).
    * Integrated registration into the Admin Menu.

### 🟡 Version 0.5 - 0.8: Staff & Table Management
* **v0.5 (Major Update):** * Launched Staff Payroll Management.
    * Built the Table Management foundation (set/alter table types and counts).
    * Implemented an automatic Table ID update system for future menu syncing.
* **v0.6:** * Integrated Table Management into the Admin Menu.
    * Started the foundation for the Staff login system.
* **v0.7:** * Finalized Staff login access.
    * Created specific menus for Waiters, Chefs, and Managers.
    * Added Table Booking (Pre-booking & Walk-ins) to the Manager system.
* **v0.8:** Refined UI and finalized database access across all active modules.

### 🔴 Version 1.0 - 1.4: Workflow & Customer Modules
* **v1.0 (Major Update - Staff):** * **Chef System:** Added Cooking Status updates and Inventory Usage modules.
    * **Waiter System:** Added Serving Status updates.
    * Synced all workflow updates with the Food Menu database.
* **v1.1:** General bug fixes and stability improvements.
* **v1.2 (Major Update - Customer):** * Launched Customer Registration and Login.
    * Implemented Table Pre-booking with a Calendar feature.
    * Added the Food Ordering Menu.
* **v1.3:** * Added Feedback/Review system.
    * Added Customer Profile update functionality.
* **v1.4:** * Implemented Argon2 & SHA-256 Password Encryption across all actors (Admin, Staff, Customer).
    * Integrated transaction processing for payments.
    * Added Waiter confirmation keys for bill payments.

### 🏆 Version 1.5 - 2.0: Analytics & Final Release
* **v1.5 (Major Update):** * Added "Restaurant Scenario" Dashboard for Admins.
    * Features: Profit/Loss calculation, expense tracking, and overall rating display.
    * Added sales analytics (Most Ordered Dish and Total Sales).
* **v1.6:** Integrated transaction logging for Payroll and Inventory in the Admin system.
* **v2.0 (Final Release):** * Final review and full-scale testing.
    * All modules fully functional and UI polished.
