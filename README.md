# The BookShelf - PHP Project

This is a PHP-based project for managing book inventory, user authentication, and order processing.

## Available Scripts

In the project directory, you can run the following scripts:

### `php -S localhost:8000`

Runs the PHP development server.\
Open [http://localhost:8000](http://localhost:8000) to view the project in your browser.

Make sure you have PHP installed on your machine. This will serve the project locally.

### Database Setup

To set up the database:

1. Create a database in MySQL (or your preferred database system).
2. Update your database connection settings in the `config.php` or `.env` file.

Example `.env` or `config.php` setup:

```php
DB_HOST=localhost
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
