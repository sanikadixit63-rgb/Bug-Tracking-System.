# Screens and Navigation

This document lists all screens in the Bug Tracking System and how users navigate between them.

## Authentication Screens
- Login Page: Allows users to log in using email and password.
- Signup Page: Allows new users to register.

After successful login, users are redirected based on their role.

## Admin Screens
- Admin Dashboard:
  - Displays all bugs in the system.
  - Shows bug status and assigned developer.
  - Provides options to create and assign bugs.

- Bug Details Page:
  - Displays detailed information about a selected bug.
  - Allows Admin to update bug status and assignment.

## Developer Screens
- Developer Dashboard:
  - Displays only bugs assigned to the logged-in developer.
  - Shows current status of each bug.

- Bug Details Page:
  - Displays detailed bug information.
  - Allows Developer to update bug status.

## Navigation Flow
- Unauthenticated users can only access Login and Signup pages.
- After login:
  - Admin users are redirected to the Admin Dashboard.
  - Developer users are redirected to the Developer Dashboard.
- Users can navigate from dashboards to individual bug details pages.
