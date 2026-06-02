#  Kamgaon Junior College Library Management System

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-College%20Use-green)
![Build](https://img.shields.io/badge/build-passing-brightgreen)

##  Live Demo
**[https://india-web.github.io/khss_library/](https://india-web.github.io/khss_library/)**

>  ## **Note**: This is a secure system. You need login credentials to access. Contact college library staff for access.
## System Overview

A comprehensive Library Management System designed specifically for **Kamgaon Junior College, Kamgaon** to digitize and streamline library operations.

### User Roles & Access

| Role | Access Level | Permissions |
|------|-------------|-------------|
| Admin | Full Control | Add/Edit/Delete everything, Import/Export data |
| Librarian | Management | Complete library management features |
| Staff | Limited | View catalog, Issue/Return books only |

###  Key Features

####  Book Management
- Add/Edit/Delete books
- Categorize by: Science, Arts, Commerce, Mythology, General Knowledge, Others
- Bulk import from Excel
- Export catalog to Excel/PDF
- Search and filter by category

####  Student Management
- Register new students
- Import student data from Excel
- Store: Name, Roll No, Stream, Year, Parent details, Mobile
- Search student records

####  Transaction Management
- Issue books to students
- Return books with automatic availability update
- Track issue & due dates
- Overdue book reminders
- Search transaction history

####  Staff Management
- Staff profiles with photos
- Contact information
- Qualifications & joining dates

#### Reports
- Export catalog to Excel
- Export catalog to PDF
- Overdue book alerts

##  Deployment Instructions

### For College IT Staff:

1. **Clone or download** this repository
2. **Update credentials** in `AUTHORIZED_USERS` object:
   ```javascript
   const AUTHORIZED_USERS = {
     admin: { password: "YOUR_SECURE_PASSWORD", ... },
     librarian: { password: "LIBRARY_PASSWORD", ... }
   };
