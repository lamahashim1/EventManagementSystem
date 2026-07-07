# Event Management System

## Overview
The Event Management System is a comprehensive web application developed as a graduation project. It provides a platform to efficiently organize, manage, and track various events and activities. Built using Python and the Django web framework, this system caters to administrators, coordinators, event heads, and participants, ensuring a seamless experience from event creation to registration and execution.

## Features
* User Authentication and Authorization: Secure login and role-based access control for different user types (Administrator, Coordinator, Event Head, Participant).
* Event Creation and Management: Easy-to-use interface for creating new events, setting dates, locations, and descriptions.
* Participant Registration: Users can easily browse available events and register to participate.
* Dashboard Panels: Dedicated dashboards for each role to track progress, monitor attendance, and manage tasks.
* Responsive Design: The web interface is responsive and accessible across different devices.

## Technologies Used
* Backend: Python, Django
* Database: SQLite
* Frontend: HTML, CSS, JavaScript
* Styling: MDB (Material Design for Bootstrap)

## Project Structure
* Administrator: Modules and views for high-level system management.
* Coordinator: Tools for event coordination and oversight.
* EventHead: Management tools specific to individual event heads.
* UserManager: Handles user profiles and authentication logic.
* EventWebSite: Public-facing pages for event browsing and registration.

## Setup Instructions

### Prerequisites
* Python 3.x installed on your machine.
* Git for version control.

### Installation
1. Clone the repository:
   git clone https://github.com/lamahashim1/EventManagementSystem.git

2. Navigate to the project directory:
   cd EventManagementSystem

3. Create and activate a virtual environment:
   python -m venv venv
   venv\Scripts\activate  (On Windows)

4. Install the required dependencies:
   pip install -r requirements.txt

5. Apply database migrations:
   python manage.py migrate

6. Run the development server:
   python manage.py runserver

7. Open your web browser and visit `http://127.0.0.1:8000/`

## License
This project is part of a university graduation requirement and is intended for educational purposes.
