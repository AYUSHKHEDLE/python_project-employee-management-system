# Project Statement: Employee Management System (EMS)

## Problem Statement

Many small-scale organizations still rely on decentralized methods like spreadsheets or physical files for managing employee data. This practice often leads to data redundancy, difficulty in searching specific records, and a significant lack of security.

The objective of this project is to provide a reliable, persistent, and secure software solution that streamlines fundamental employee data manipulation tasks (CRUD operations) while restricting access through a password-protected login mechanism.

---

## Scope of the Project

The scope of this project is limited to a **database-driven console application** that performs core administrative functions. The system focuses on:
**User Authentication:** Ensuring system access is secured and restricted.
**Data Persistence:** Storing data in a MySQL database using defined tables (`logid`, `office`, and `performance`)
* **Core CRUD Operations:** Handling the registration, retrieval, and updating of employee records.
* **Basic Reporting:** Providing counts and formatted lists of current employees.

The scope does **not** include a graphical user interface (GUI) or advanced features like password hashing or search filtering.

---

## Target Users

The primary target users for the Employee Management System are:

**System Administrators:** Individuals responsible for setting up user accounts and maintaining system security.
**HR/Management Staff:** Users who need to register new employees, update salaries, and retrieve employee performance and demographic data.

---

## High-level Features

The system's features are designed around the central program execution loop defined in the workflow.

**Secure system:** Mandatory user **Login** and **Registration**.
**Record Management:** Functions for **Employee Registeration** (Create) and **Employee Details** viewing (Read).
