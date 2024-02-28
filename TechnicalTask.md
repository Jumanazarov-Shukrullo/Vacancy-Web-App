# Technical Task: Vacancy Web App

## Overview

The goal of this project is to develop a full-stack web application using Flask framework for managing job vacancies. The application should allow users to perform CRUD operations on vacancies and include user authentication. Additionally, it should be deployable using Docker and capable of parsing data from another web application.

## Requirements

1. **User Authentication**:
   - Users should be able to sign up, log in, and log out securely.
   - Only authenticated users should be able to perform CRUD operations on vacancies.

2. **CRUD Operations**:
   - Authenticated users should be able to create, read, update, and delete job vacancies.
   - Each vacancy should have fields such as title, description, company name, location, etc.

3. **Search Functionality**:
   - Users should be able to search for vacancies based on various criteria, such as title, company name, location, etc.

4. **Responsive Design**:
   - The application should be responsive and work well on different screen sizes and devices.

5. **Database**:
   - Use SQLite for development and PostgreSQL for production.
   - Use SQLAlchemy ORM for managing database operations.

6. **Deployment with Docker**:
   - The application should be deployable using Docker containers.
   - Provide Dockerfiles and docker-compose configuration for setting up the development and production environments.

7. **Data Parsing from Another Web App**:
   - Implement functionality to parse data from another web application (e.g., a job aggregator website) and display it within the application.
   - The parsed data should be stored in the application's database and displayed alongside manually added vacancies.

## Technologies

- **Frontend**:
  - HTML, CSS, JavaScript
  - Bootstrap (for styling)

- **Backend**:
  - Python
  - Flask framework
  - SQLAlchemy (for database management)

- **Database**:
  - SQLite (for development)
  - PostgreSQL (for production)

- **Deployment**:
  - Docker
  - Kubernetes

## Implementation Details

- Use Flask's built-in authentication system or Flask-Login extension for user authentication.
- Implement CRUD operations for vacancies using Flask routes and SQLAlchemy ORM.
- Create appropriate database models for vacancies and users.
- Implement search functionality using Flask routes and SQLAlchemy queries.
- Ensure proper validation and error handling mechanisms.
- Use Bootstrap for frontend styling and ensure responsiveness.
- For deployment with Docker, provide Dockerfiles and docker-compose configuration files.
- Implement a mechanism to fetch and parse data from another web application, storing it in the application's database.
