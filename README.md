# Online Learning Management System (eLearning Platform with Laravel)

![Project Banner](link-to-banner-image)

## Introduction

The Online Learning Management System is an eLearning platform built using Laravel. It provides a comprehensive solution for offering both free and paid courses, allowing students to acquire new skills through enrollment. This platform incorporates various features to facilitate a seamless learning experience for users.

## Features

- **User Authentication:** Users can sign up, log in, and manage their accounts securely.
- **Roles and Permissions:** Different user roles such as SuperAdmin, Instructor, and Student with distinct permissions.
- **Course Management:** Instructors can create and publish courses, while students can enroll in them.
- **Course Categories and Types:** Courses are organized into different categories and types for easy navigation.
- **Profile Management:** Users can manage their profiles, update information, and view their enrolled courses.
- **Shopping Cart and Checkout:** Users can add courses to their cart and complete the checkout process for paid courses.
- **Course Enrollment:** Students can enroll in courses they are interested in and access course materials.
- **Content Viewing:** Enrolled students can view course contents, including videos, documents, and etc.
- **Search Filters:** Users can search for courses based on various filters such as category, and etc.

## Technology Stack

- **Framework:** Laravel
- **Template Engine:** Laravel Blade
- **Database:** MySQL
- **Frontend:** HTML, CSS, jQuery, etc.

## Demo Credentials

- **SuperAdmin:** 
  - Email: admin@gmail.com
  - Password: 123
- **Instructor:** 
  - Email: fuad@gmail.com
  - Password: 123

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository.
2. Install dependencies `composer install` (If composer not install, install first).
3. Copy the `.env.example` file to `.env` or rename the file to `.env`.
4. Configure the database settings in the `.env` file.
5. Generate application key `php artisan key:generate`.
6. Start XAMPP Apache server and MySQL service.
7. Create only the database with the same name as the one in `.env` file.
8. Run the migrations `php artisan migrate`.
9. Run `php artisan db:seed` or `php artisan migrate --seed`.
10. Set up front-end assets `npm install` (Install node.js if not installed).
11. Then run `npm run dev`. Do not close this terminal.
12. Open a new terminal and start the development server `php artisan serve`.
13. Go to the address the server running on, usually 127.0.0.1:8000 or localhost:8000
14. To get into admin page, create an account and then manually change "full_access" attribute value from 0 to 1 
    by going to the users table and editing in the database directly. Then after login you have all controls.

## Contributing

Contributions are welcome! Please follow the contribution guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
