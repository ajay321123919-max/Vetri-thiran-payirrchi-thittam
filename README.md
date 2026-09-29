# Script-Controlled ACL – ServiceNow Project

This repository is organized into the same 8-stage project structure shown in the reference screenshot.

## Project
**Script-Controlled ACL – Restrict Record Access Based on Field Value**

### Platform
ServiceNow

### Custom Table
`u_institution_details`

### Security Model
Script-controlled ACL with role-based and Branch-based record access.

## Repository Structure

1. Brainstorming & Ideation
2. Requirement Analysis
3. Project Design Phase
4. Project Planning
5. Project Development
6. Project Testing
7. Project Documentation
8. Project Demonstration

## CRUD Permissions

| Operation | Role |
|---|---|
| READ | bb1 + Branch = EEE |
| CREATE | bb2 |
| WRITE | bb3 |
| DELETE | bb4 |

Administrators retain full access.

> This repository structure was prepared from the supplied Script-Controlled ACL project documentation.
