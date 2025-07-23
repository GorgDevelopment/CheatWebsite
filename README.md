# Cheat Website Management System

> ⚠️ **Note**: This is an archived project from my earlier development days. While functional, it may not follow all current best practices and security standards.

A PHP-based web application for managing game cheat subscriptions and user access. This project demonstrates basic user authentication, admin controls, and subscription management functionality.

## 🚀 Features

- **User Management**
  - User registration and authentication
  - Profile management
  - Ban system for violating users

- **Admin Dashboard**
  - Comprehensive admin panel
  - User activity monitoring
  - Cheat status management
  - Version control for cheat releases
  - Maintenance mode toggle
  - Invite system management

- **Subscription System**
  - Subscription management
  - Download access control
  - API integration support

## 💻 Tech Stack

- PHP
- MySQL
- Bootstrap 4
- JavaScript
- Custom CSS

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/CheatWebsite.git
```

2. Import the database structure:
- Create a new MySQL database
- Import the `DB.sql` file into your database

3. Configure the application:
- Navigate to `app/core/Config.php`
- Update the database credentials and other configuration settings

4. Set up your web server:
- Configure your web server (Apache/Nginx) to point to the project directory
- Ensure PHP is installed and configured properly
- Enable required PHP extensions (mysqli, etc.)

5. Set proper permissions:
- Ensure write permissions for logs and upload directories
- Secure sensitive files and directories

## 📁 Project Structure

```
CheatWebsite/
├── admin/           # Admin panel files
├── app/             # Core application files
│   ├── controllers/ # Application controllers
│   ├── core/        # Core functionality
│   └── models/      # Data models
├── assets/          # Static assets (CSS, JS)
├── bootstrap/       # Bootstrap framework files
└── includes/        # Reusable PHP components
```

## 👥 User Roles

- **Admin**: Full access to admin panel and all features
- **Users**: Access to subscribed features and personal profile
- **Banned Users**: Restricted access

## ⚠️ Security Notice

This is an old project and may not implement all current security best practices. If you plan to use this in a production environment, please:

- Update all dependencies to their latest versions
- Implement proper input validation and sanitization
- Add additional security measures (2FA, rate limiting, etc.)
- Review and update the authentication system
- Implement proper CSRF protection
- Use prepared statements for all database queries

## 📝 License

This project is open-source and available under the MIT License.

## ⚡ Quick Start for Development

1. Set up a local PHP development environment (XAMPP/WAMP/MAMP)
2. Clone the repository to your web server directory
3. Import the database structure
4. Configure the application settings
5. Access the website through your local development URL

## 🤝 Contributing

While this is an archived project, feel free to fork and improve upon it. If you make significant improvements, consider sharing them with the community.

## 📫 Support

This is an archived project and may not receive active support or updates. Feel free to fork and modify as needed for your own use. 
