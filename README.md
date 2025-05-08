
Built by https://www.blackbox.ai

---

# EduRecruit - Admin Dashboard

## Project Overview
EduRecruit is an online admin dashboard designed for managing applicants, agents, universities, and courses in the education sector. The dashboard provides vital statistics, lists, and functionalities that streamline administrative processes, allowing administrators to monitor key metrics and engage with different entities efficiently.

## Installation
To get started with the EduRecruit project, follow these installation steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/edurecruit.git
   ```
2. Navigate into the project directory:
   ```bash
   cd edurecruit
   ```
3. Open the `index.html` file in your favorite web browser to view the dashboard.

## Usage
Explore the dashboard through various sections:
- **Dashboard**: Overview of total applicants, active agents, universities, and courses.
- **Applicants**: View and manage applicant information, including search and sorting capabilities.
- **Agents**: Monitor the performance of agents based on various metrics.
- **Universities**: Access the list of partnered universities and manage data.
- **Courses**: Oversee courses offered by various universities.
- **Reports**: Generate insightful reports on applicants, agents, and courses for better decision-making.
- **Profile**: Manage user account settings.

## Features
- Real-time statistics display on the main dashboard.
- Detailed views and management options for applicants, agents, universities, and courses.
- Responsive design built with Tailwind CSS, ensuring compatibility across devices.
- Easy navigation through sidebar menus.
- Search and filter functionalities in lists.
- Profile management section for user account settings.

## Dependencies
This project requires the following dependencies:
- **Tailwind CSS**: For styling the user interface.
- **jQuery**: For handling interactions and dynamic elements.

To include them, ensure your `index.html` file has the following links in the `<head>` section:
```html
<script src="https://cdn.tailwindcss.com"></script>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
```

## Project Structure
The project is structured as follows:
```
/edurecruit
│
├── index.html          # Main dashboard page
├── applicants.html     # Applicants management page
├── agents.html         # Agents management page
├── universities.html    # Universities management page
├── courses.html        # Courses management page
├── reports.html        # Reports page
├── profile.html        # User profile page
├── profile-edit.html    # Edit user profile page
├── css/                # (optional) Directory for custom styles
└── js/                 # (optional) Directory for custom scripts
```

Feel free to explore and modify the code as per your requirements! For support or contributions, open an issue or a pull request in the repository.

## License
Distributed under the MIT License. See `LICENSE` for more information.