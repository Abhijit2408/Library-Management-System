# Library-Management-System
Overview
The Library Management System (LMS) is designed to streamline the process of managing library resources, facilitating user interactions, and generating necessary reports. 
This application includes features for both administrators and regular users, focusing on book transactions, membership management, and reporting functionalities.

# Features

# User Roles
* Admin: Full access to Maintenance, Reports, and Transactions modules.
* User: Access to Reports and Transactions only.

# Key Modules
* Maintenance (Admin only)
* Reports (Available to both Users and Admin)
* Transactions (Available to both Users and Admin)

# User Interface
* Navigation: A chart link is provided on all pages for easy navigation.
* Form Elements: Includes radio buttons, checkboxes, and password fields with specific behaviors.

# Functionalities
* Book Issue: Allows users to issue books with automatic population of author names and controlled issue/return dates.
* Return Book: Users can return books, with mandatory fields ensuring proper data entry.
* Fine Payment: Facilitates fine payments before returning books, with clear error handling.
* Membership Management: Users can add or update their membership details.
* Book Management: Administrators can add or update book records.

# Validations
* Form submissions require at least one input.
* Error messages guide users for invalid submissions.
