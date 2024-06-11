# Task List App

This application provides a simple and intuitive interface for managing tasks and organizing daily activities. It is developed using HTML, CSS, MySQL, PHP, and Laravel.

## Features

- **Add Tasks**: Create new tasks with titles and descriptions.
- **Edit Tasks**: Modify existing tasks to update details.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Task List View**: View a list of all tasks with their status (completed or pending).
- **Mark as Complete**: Mark tasks as completed to keep track of progress.
- **Responsive Design**: User-friendly interface compatible with both desktop and mobile devices.

## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS**: For styling the web pages.
- **MySQL**: For database management.
- **PHP**: For server-side scripting.
- **Laravel**: For a robust and scalable PHP framework.


## To run this project locally, follow these steps:

1)Clone the repository:
git clone https://github.com/yourusername/task-list-app.git
cd task-list-app

2)Install dependencies:
Make sure you have Composer installed. Then run:
composer install

3)Set up the environment:
Copy the .env.example file to .env and update the necessary environment variables (database credentials, etc.):
cp .env.example .env

4)Set up the database:
Create a new MySQL database and update your .env file with the database credentials. Then run the migrations:
php artisan migrate

5)Serve the application:
Start the local development server:
php artisan serve

6)Access the application:
Open your browser and go to http://localhost:8000.
