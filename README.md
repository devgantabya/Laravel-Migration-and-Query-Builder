Laravel Migration and Query Builder
A collection of examples, best practices, and templates for using Laravel Migrations and Query Builder. This repository helps you quickly understand how to manage database schemas and perform database operations efficiently using Laravel’s built-in tools.

📦 Features
📄 Migrations:

Creating, updating, and dropping tables

Managing foreign keys and indexes

Best practices for rollback and version control

🛠️ Query Builder:

Insert, update, delete, select operations

Joins, aggregates, and subqueries

Using raw expressions safely

📚 Additional Resources:

Useful artisan commands

Tips for writing clean, efficient queries

Real-world examples and common patterns

🚀 Getting Started
Requirements
PHP 8.2+

Laravel 12+

Database (MySQL, PostgreSQL, SQLite, etc.)

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Laravel-Migration-and-Query-Builder.git
cd Laravel-Migration-and-Query-Builder
Then explore the migrations/ and query-builder-examples/ folders to see practical examples.

📂 Folder Structure
pgsql
Copy
Edit
├── migrations/
│   ├── create_users_table.php
│   ├── create_posts_table.php
│   └── add_profile_to_users_table.php
├── query-builder-examples/
│   ├── select-examples.php
│   ├── insert-update-delete.php
│   └── join-queries.php
└── README.md
🧠 Usage
Use the migrations folder as a reference when building or updating your own Laravel migrations.

Use the query-builder-examples folder to find ready-to-use query builder examples.

Copy, adapt, and modify as needed for your projects!

🎯 Purpose
This repository aims to:

Help beginners learn database operations in Laravel.

Provide ready examples for quick development.

Encourage best practices for database management.

📖 Useful Artisan Commands

Command	Purpose
php artisan migrate	Run all migrations
php artisan migrate:rollback	Rollback the last migration batch
php artisan migrate:fresh	Drop all tables and re-run all migrations
php artisan make:migration create_posts_table	Create a new migration file
🤝 Contributing
Contributions are welcome!
If you have a helpful migration or query builder example, feel free to open a pull request.

📄 License
This project is open-sourced under the MIT license.
