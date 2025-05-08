
Built by https://www.blackbox.ai

---

# EduRecruit - Admin Dashboard

## Project Overview
EduRecruit is an admin dashboard application designed to manage the recruitment process for educational institutions. The dashboard provides functionality for monitoring applicants, agents, universities, and courses, making it easier for administrators to manage the recruitment cycle effectively.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/edurecruit.git
   cd edurecruit
   ```

2. Open the `index.html` file in your preferred web browser. The application does not require any server configuration and runs on the frontend.

## Usage
Simply open `index.html` in a web browser to access the dashboard. Use the sidebar navigation to switch between different sections of the dashboard including:

- Dashboard
- Applicants
- Agents
- Universities
- Courses
- Reports
- Profile

## Features
- **Responsive Design**: Built with Tailwind CSS for a mobile-friendly layout that adapts to various screen sizes.
- **Dashboard Overview**: Displays key metrics regarding total applicants, active agents, partnered universities, and available courses.
- **Applicants Management**: A complete section for viewing and managing applicant information.
- **Agent Management**: Features a dedicated section for tracking agents involved in the recruitment process.
- **University Management**: Administrators can easily add and manage partner universities.
- **Course Management**: The option to add and update available courses.
- **Reporting**: Generate reports for applicants and various metrics.
- **User Profiles**: Manage user profiles with options for editing details and changing passwords.

## Dependencies
The project utilizes the following external libraries:
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- [jQuery](https://jquery.com/)

Include the following in your project to ensure compatibility:
```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>
<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<!-- jQuery -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

## Project Structure
The project consists of multiple HTML files representing different sections of the dashboard:
```
.
├── index.html          # Main dashboard page
├── applicants.html     # Applicants management page
├── agents.html        # Agents management page
├── universities.html    # Universities management page
├── courses.html        # Courses management page
├── reports.html        # Reports page
├── profile.html        # User profile page
├── profile-edit.html    # Edit user profile page
```

Each HTML file contains a consistent structure, utilizing Tailwind CSS for styling and jQuery for interactivity.

---

For more details and updates, please check the project's repository.