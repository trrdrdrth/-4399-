# Game Portal

Welcome to the Game Portal project! This is a web-based platform that allows users to play a variety of games directly in their browsers. The project includes a backend server, a client application, and an admin panel for managing users and games.

## Features

- **User Registration and Login**: Users can create accounts and log in to access the platform.
- **Game Library**: A collection of 100+ games that can be played directly in the browser.
- **Developer Application**: Developers can apply to upload their games, which will be subject to admin approval.
- **Admin Dashboard**: Admins can manage users, approve developer applications, and oversee game uploads.
- **Responsive Design**: The platform is designed to be responsive and works on all devices.

## Project Structure

- **backend**: Contains the server-side code, including controllers, routes, models, and services.
- **client**: Contains the client-side code, including React components and pages.
- **admin**: Contains the admin panel code for managing the platform.
- **games**: Contains game files and manifests.
- **scripts**: Contains scripts for database seeding and migration.
- **migrations**: Contains database migration files.
- **prisma**: Contains the Prisma schema for database modeling.
- **tests**: Contains test files for backend, client, and admin.
- **docs**: Contains documentation for architecture and API.
- **.env.example**: Example environment variables file.
- **docker-compose.yml**: Docker configuration for the project.

## Getting Started

1. Clone the repository:
   ```
   git clone <repository-url>
   cd game-portal
   ```

2. Install dependencies for the backend:
   ```
   cd backend
   npm install
   ```

3. Install dependencies for the client:
   ```
   cd client
   npm install
   ```

4. Set up the database and run migrations:
   ```
   cd scripts
   ts-node migrate.ts
   ```

5. Start the backend server:
   ```
   cd backend
   npm start
   ```

6. Start the client application:
   ```
   cd client
   npm start
   ```

7. Access the application in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
