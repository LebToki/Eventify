# Eventify - Event Management System
Elevate Your Events with Eventify!

Eventify is your all-in-one platform for seamless event management, designed to simplify the complexities of organizing events, managing freelance talent, and coordinating with clients. This Laravel-based application brings together powerful features to help you plan, manage, and execute events effortlessly.

# Features

- User Management: Manage users with roles (Admins, Freelancers, Clients, etc.).
- Country and City Management: Add, edit, and organize countries and cities with search and pagination.
- Event Management: Track and manage events, including schedules, venues, and participants.
- Freelancer Management: Add and monitor freelancers assigned to events.
- Asset Management: Organize resources and materials for your events.
- Notification System: Real-time notifications to keep users updated.
- Dashboard Overview: A fully customizable dashboard with statistics, upcoming events, and a calendar view.
- Authentication: Secure login, registration, forgot password, and email verification.
- Responsive Design: Designed with a responsive layout using Bootstrap, ensuring a seamless experience on any device.
- Dark Mode: Switch between light and dark themes for a personalized experience.

#Installation

- Prerequisites
- PHP >= 8.1
- Composer
- MySQL
- Node.js and npm

# Steps
- Clone the repository:

`
git clone https://github.com/LebToki/eventify.git
`

Navigate to the project directory:

`
cd eventify
`

- Install PHP dependencies:

`
composer install
`

# Install JavaScript dependencies:

`
npm install && npm run dev
`

# Create a .env file by copying the example file:
`
cp .env.example .env
`

# Configure the .env file with your database and mail settings.
- Generate the application key:

`
php artisan key:generate

# Run the migrations:

`
php artisan migrate --seed
`

Serve the application:
`
php artisan serve
`

# Usage

- Authentication
- Visit /login to log in as an admin or a user.
- Admin credentials (created by seeder):
- Email: admin@example.com
- Password: admin123

- Dashboard
After logging in, access the dashboard to view statistics, upcoming events, and more.

- Country & City Management
Use the country and city management modules to organize geographical data.

# Technologies Used
- Backend: Laravel 11
- Frontend: Blade Templates, Bootstrap 5
- Database: MySQL
- Notifications: Laravel Notifications
- Authentication: Laravel Breeze
- Icons: Boxicons
- Styling: SCSS, Bootstrap
- Dark Mode: JavaScript & CSS

# Development

- Directory Structure
- routes/: Contains web.php for web routes and api.php for API routes.
- resources/views/: Blade templates for UI, including layouts and partials.
- app/Models/: Models for countries, cities, events, users, etc.
- app/Http/Controllers/: Controllers to handle logic for various modules.

# Contributing
We welcome contributions! To contribute:

# Fork the repository.
Create a new branch for your feature:

`
git checkout -b feature/your-feature
`

Push your branch:
`
git push origin feature/your-feature
`

Submit a pull request.

# License
This project is licensed under the Private License.

# Author
Tarek Tarabichi
Reach out to me via email for any queries or suggestions.
Let me know if you your organization would benefit of anything similar to this with changes or enhancements!
