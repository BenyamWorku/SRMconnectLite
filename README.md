# SRMconnectLite
SRMconnect is a web app for managing student relationships, attendance, and progress reports with secure login for admins, tutors, and social workers.


detailed features broken down by the main features:
# 1. User Management
## 1.1 User Authentication
  * User registration
  * User login/logout : consider passwordless login too.
  * Password reset
  * JWT token generation on successful login
  * JWT token verification on API calls
  * Error handling for authentication errors
## 1.2 User Authorization
  * Authorization middleware for each user role
  * Role-based access control (RBAC) implementation
  * Admin panel for managing user accounts and roles
  * Error handling for authorization errors
## 1.3 User Dashboard
  * Separate dashboard for each user role
  * Display relevant information for each user role on the dashboard
  * Navigation menu to access other sections of the app
  * Error handling for dashboard loading errors
## 1.4 User Account Management
  * User profile page with editable user details
  * Update user details API endpoint
  * Password change form and API endpoint
  * Delete user account API endpoint
  * Error handling for account management errors

# 2 Dashboard
## 2.1 Attendance and Progress Dashboard
  * Separate dashboard for tutors to view attendance and progress reports
  * Display attendance and progress data for each student
  * Pagination and search functionality for attendance and progress report list
  * Export attendance and progress data as CSV or PDF
  * Error handling for dashboard loading errors

## 2.2 Student List Dashboard
  * Dashboard for admin to view information about all students
  * Display list of all students with relevant information
  * Search and filter functionality for student list
  * Delete student confirmation modal
  * Error handling for dashboard loading and student deletion errors
# 3. Social Worker Dashboard
## 3.1 Dashboard for Social Workers
  * Dashboard for social workers to view attendance and progress reports
  * Display attendance and progress data for each student
  * Display test results on student profile page
  * Error handling for dashboard loading errors

# 4. Webhosting Details
## 4.1 Hosting Information
  * Information on web hosting options and requirements
  * Server setup guide for the chosen hosting provider
  * Environment variables management for different hosting environments
  * Error handling for hosting information loading errors
## 4.2 Deployment
  * Deployment scripts for the chosen hosting provider
  * SSL certificate installation and configuration
  * Backup and restore procedures for the database
  * Error handling for deployment errors
# 5. Security
## 5.1 Password Security
  * Password encryption and salting
  * Password reset functionality with email verification
