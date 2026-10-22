# Bolsa de Empleo

A university team project for managing job opportunities and candidate applications. The system includes a React frontend and a Java REST API backed by MySQL.

## Features

- Browse and search recent job postings.
- Register as a company or job seeker and authenticate with JWT.
- Manage company postings and review candidates.
- Maintain a job seeker profile, skills, and CV.
- Provide administration views for account approval, skill management, and reporting.

## Technology

- **Frontend:** React 18, Vite, React Router, Axios
- **Backend:** Java 21, Spring Boot 3.4, Spring Security, Spring Data JPA
- **Database:** MySQL
- **Authentication:** JWT

## My contribution

I contributed to the React frontend, including job search and reporting features.

## Run locally

You need Java 21, Maven, Node.js with npm, and a local MySQL database.

1. Configure the database connection and application settings in the backend's local configuration.
2. Start the API:

   ```sh
   cd Backend
   mvn spring-boot:run
   ```

3. In another terminal, start the frontend:

   ```sh
   cd frontend
   npm install
   npm run dev
   ```

The Vite development server proxies `/api` requests to `http://localhost:8080`. The project is intended for local academic development and does not have a public demo.
