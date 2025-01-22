# InovTrack

InovTrack is a web-based platform designed to automate task assignments for students based on their skills. The system targets students in technical fields such as computer science and engineering. It uses ReactJS for the frontend, Python for the backend, and SQL (PostgreSQL or MySQL) for the database.

## Features

- **Backend:**
  - Built using Python, implementing CRUD (Create, Read, Update, Delete) operations to manage student profiles and task assignments.
  - Utilizes LLaMA (Large Language Model) for analyzing GitHub project README files and extracting relevant technical skills required for each project.

- **Frontend:**
  - Developed with ReactJS, allowing users to interact with the platform, view their assigned tasks, and manage profiles.

- **Task Assignment Automation:**
  - Automatically scrapes GitHub repositories to extract README content.
  - Uses LLaMA to analyze the README and extract key skills required for the project.
  - Matches the extracted skills with predefined student profiles.
  - Assigns tasks to students based on the match between their skills and the skills required by the GitHub project.

## Student Profiles

The student profiles include information on their technical skills. Example profiles are:

- **Santhosh:** Python, Flask, API, Watchdog
- **Vishnu:** Web development, Git, Flask
- **Saran:** Linux, Python, Security, Watchdog, Yara

## Getting Started

### Prerequisites

- Python 3.x
- Node.js and npm
- PostgreSQL or MySQL
- ReactJS

### Backend Setup

1. Clone the repository.
2. Install the required dependencies for the Python backend.
3. Set up the database (PostgreSQL/MySQL).
4. Configure environment variables.
5. Run the backend server.

### Frontend Setup

1. Navigate to the frontend directory.
2. Install the necessary dependencies using npm.
3. Run the React development server.

### Task Assignment Process

1. GitHub repositories are scraped for README files.
2. LLaMA analyzes the README content to extract relevant technical skills.
3. These skills are matched with student profiles.
4. Tasks are automatically assigned to students based on their skills.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License.
