# Laravel E-Commerce App

This is a Laravel-based e-commerce application that supports products, categories, brands, and units. It also includes a user authentication system, product image uploads, and a responsive Bootstrap front end.

## 📦 Features

- Admin and user authentication
- Product CRUD (Create, Read, Update, Delete)
- Category, Brand, and Unit management
- Product image upload and display
- Search and pagination
- Responsive UI using Bootstrap

## 🚀 Getting Started

These instructions will help you set up the project on your local machine.

### 🛠 Requirements

- PHP >= 8.1
- Composer
- MySQL
- Node.js and NPM
- Laravel 10+

### 🔧 Installation

# 2. Install PHP dependencies
composer install

# 3. Copy the .env file and configure
cp .env.example .env
php artisan key:generate

# 4. Set your DB credentials in .env
# DB_DATABASE=your_db
# DB_USERNAME=root
# DB_PASSWORD=

# 5. Run migrations and seeders
php artisan migrate --seed

# 6. Install NPM dependencies (optional)
npm install && npm run dev
