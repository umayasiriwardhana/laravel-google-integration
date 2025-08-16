# Laravel Google Integration App

This is a Laravel application that allows users to log in with their Google account using OAuth2 and Laravel Socialite. It is being extended to support the following features:

- ✅ Google Login via OAuth
- 🔄 Google Calendar Integration (Upcoming)
- 📧 Google Email (Gmail) Access (Upcoming)
- 📝 Google Tasks (To-Dos) Display (Upcoming)

---

## 🚀 Features

- Laravel 12.x
- Google OAuth2 Login
- Socialite for authentication
- Responsive UI using Blade
- HTML tables for displaying fetched data (Calendar, Emails, ToDos)

---

## 🛠️ Requirements

- PHP >= 8.2
- Composer
- Laravel 12
- Google Developer Console credentials
- MySQL or SQLite

---

## 🔧 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/laravel-google-integration.git

# Go into the project folder
cd laravel-google-integration

# Install dependencies
composer install

# Create a .env file
cp .env.example .env

# Generate app key
php artisan key:generate

# Configure database and Google credentials in `.env`

