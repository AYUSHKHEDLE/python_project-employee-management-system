# Project Statement: Employee Management System (EMS)

## Problem Statement

[cite_start]Many small-scale organizations still rely on decentralized methods like spreadsheets or physical files for managing employee data[cite: 191]. [cite_start]This practice often leads to data redundancy, difficulty in searching specific records, and a significant lack of security[cite: 192].

[cite_start]The objective of this project is to provide a reliable, persistent, and secure software solution that streamlines fundamental employee data manipulation tasks (CRUD operations) while restricting access through a password-protected login mechanism[cite: 193, 194].

---

## Scope of the Project

[cite_start]The scope of this project is limited to a **database-driven console application** [cite: 137] [cite_start]that performs core administrative functions[cite: 197]. The system focuses on:
* [cite_start]**User Authentication:** Ensuring system access is secured and restricted[cite: 194, 201].
* [cite_start]**Data Persistence:** Storing data in a MySQL database [cite: 137] [cite_start]using defined tables (`logid`, `office`, and `performance`)[cite: 230].
* **Core CRUD Operations:** Handling the registration, retrieval, and updating of employee records.
* **Basic Reporting:** Providing counts and formatted lists of current employees.

[cite_start]The scope does **not** include a graphical user interface (GUI) or advanced features like password hashing [cite: 370] [cite_start]or search filtering[cite: 372].

---

## Target Users

The primary target users for the Employee Management System are:

* [cite_start]**System Administrators:** Individuals responsible for setting up user accounts and maintaining system security[cite: 200].
* [cite_start]**HR/Management Staff:** Users who need to register new employees, update salaries, and retrieve employee performance and demographic data[cite: 186, 204].

---

## High-level Features

[cite_start]The system's features are designed around the central program execution loop defined in the workflow[cite: 231].

* [cite_start]**Secure Access:** Mandatory user **Login** and **Registration**[cite: 232, 234].
* [cite_start]**Record Management:** Functions for **Employee Registeration** (Create) and **Employee Details** viewing (Read)[cite: 234, 235]].
