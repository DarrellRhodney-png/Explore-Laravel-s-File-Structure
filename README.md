# Explore-Laravel-s-File-Structure
# Laravel Project: laravel_app

## Folder and File Uses

### 1. app/
Contains the core application code:
- Http/: Handles requests and responses (Controllers, Middleware)
- Models/: Represents database tables (User.php, Post.php)

### 2. config/
Holds configuration files like app.php, database.php, mail.php.
Used to set environment settings, timezone, app name, etc.

### 3. database/
Holds database-related files:
- migrations/: Scripts to create/modify tables
- seeders/: Sample data to populate tables

### 4. routes/
Defines application routes:
- web.php: Routes for web requests
- api.php: Routes for API requests

### 5. .env
Environment file storing sensitive info like database credentials, API keys.

### 6. composer.json
Lists all dependencies (packages) needed for the project.

### 7. .gitignore
Tells Git which files/folders to ignore (e.g., vendor/, .env).
