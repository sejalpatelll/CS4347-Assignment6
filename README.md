# CS 4347 — SQL Injection Assignment

**Course:** Database Systems (CS 4347) — The University of Texas at Dallas  
**Assignment:** Group Assignment 6  

---

## Overview

This project demonstrates SQL injection vulnerabilities and how to prevent them using prepared statements. Built on top of a seller database project, it includes two HTML form interfaces — a login form and a password update form — along with PHP backend logic to handle queries.

---

## What's Included

- `login_form.html` — Login form that takes Seller ID (SID) and password
- `update_form.html` — Password update form (old password → new password)
- `form_style.css` — Styling for the login form
- `update_form_style.css` — Styling for the update form

---

## Assignment Parts

**Part A — Vulnerable SELECT**  
Login form that passes user input directly into a SQL SELECT query with no sanitization, demonstrating how an injected string can bypass authentication.

**Part B — Vulnerable UPDATE**  
Password update form with the same vulnerability applied to a SQL UPDATE command, showing how injection can modify database records without proper credentials.

**Part C — Prepared Statements (Prevention)**  
Rewrites Part A using PHP prepared statements to sanitize inputs and prevent SQL injection entirely.

---

## Key Concepts Demonstrated

- SQL injection via unsanitized form inputs
- Authentication bypass using injected SQL strings
- Preventing injection with parameterized queries / prepared statements

---

## Tech Stack

- HTML / CSS
- PHP
- MySQL
