# 🔗 Link Rotator

> **Smart URL Rotation & A/B Testing Tool**

A powerful web application that creates intelligent short links capable of rotating between multiple destination URLs. Perfect for A/B testing, marketing campaigns, load balancing, and affiliate marketing.

## 🌟 Live Demo

**🚀 [Try Link Rotator Live](https://link-rotator.com)**

![Link Rotator Screenshot](screenshot.png)
*Add your screenshot here*

## ✨ Features

### 🎯 Core Functionality
- **Smart Link Rotation** - Create one short link that rotates between multiple destinations
- **Multiple Rotation Types** - Choose between Round Robin (sequential) or Random rotation
- **Custom Short Codes** - Create memorable, branded short links
- **Guest Mode** - Create temporary links without registration (7-day expiration)
- **User Accounts** - Register for permanent links and advanced features

### 📊 Analytics & Tracking
- **Real-time Analytics** - Track clicks, unique visitors, and engagement
- **Daily Statistics** - View performance trends over time
- **Browser Analytics** - See which browsers your audience uses
- **IP Tracking** - Monitor unique visitors and click patterns
- **Recent Activity** - Real-time feed of link interactions

### 🛡️ Security & Performance
- **CSRF Protection** - Secure forms with token validation
- **Rate Limiting** - Prevent abuse with intelligent rate limiting
- **Captcha Verification** - Human verification for link creation
- **Input Validation** - Comprehensive data sanitization
- **SQL Injection Protection** - Prepared statements throughout

### 👤 User Management
- **User Registration/Login** - Secure account system
- **Admin Panel** - Administrative controls and oversight
- **Role-based Access** - User and admin permission levels
- **Profile Management** - Update passwords and account settings

## 🛠️ Tech Stack

### Backend
- **PHP 7.4+** - Server-side language
- **MySQL/MariaDB** - Database storage
- **PDO** - Database abstraction layer

### Frontend
- **HTML5** - Modern markup
- **CSS3** - Custom styling with animations
- **JavaScript (Vanilla)** - Interactive functionality
- **Google Fonts** - Typography (Inter & JetBrains Mono)

### Development
- **XAMPP Compatible** - Easy local development setup
- **Session Management** - Secure user sessions
- **RESTful APIs** - Clean API endpoints

## 🎨 Key Use Cases

- **A/B Testing** - Test different landing pages or offers
- **Load Balancing** - Distribute traffic across multiple servers
- **Affiliate Marketing** - Rotate between different affiliate programs
- **Campaign Management** - Manage multiple marketing campaigns
- **Content Testing** - Test different content variations
- **Geographic Routing** - Route users to region-specific content

## 📁 Project Structure

```
link-rotator/
├── api/                    # API endpoints
│   ├── create-link.php     # Link creation
│   ├── link-analytics.php  # Analytics data
│   ├── login.php          # Authentication
│   └── ...
├── config/                 # Configuration files
│   └── database.php       # Database settings
├── dashboard/             # User dashboard
├── admin/                 # Admin panel
├── includes/              # Shared utilities
│   ├── auth.php           # Authentication helpers
│   ├── functions.php      # Core functions
│   └── captcha.php        # Captcha system
├── public/                # Static assets
│   ├── style.css          # Styling
│   └── script.js          # JavaScript
└── redirect.php           # Link redirection handler
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/link-rotator.git
   cd link-rotator
   ```

2. **Set up your web server** (Apache/Nginx with PHP support)

3. **Configure the database** in `config/database.php`

4. **Create the database** - Tables will be auto-created on first run

5. **Access the application** in your browser

## 🔧 Configuration

### Database Setup
Edit `config/database.php` with your database credentials:

```php
define('DB_HOST', 'localhost');
define('DB_USER', 'your_username');
define('DB_PASS', 'your_password');
define('DB_NAME', 'link_rotator');
```

### Default Admin Account
- **Email:** admin@linkrotator.com
- **Password:** admin123
- ⚠️ **Important:** Change these credentials after first login!

## 🌐 API Endpoints

- `POST /api/create-link.php` - Create new rotator link
- `GET /api/link-analytics.php` - Get link statistics
- `POST /api/login.php` - User authentication
- `POST /api/register.php` - User registration
- `DELETE /api/delete-link.php` - Delete link
- `PUT /api/update-link.php` - Update link settings

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- **Live Demo:** [https://link-rotator.com](https://link-rotator.com)
- **Documentation:** Coming soon
- **Support:** Create an issue on GitHub

---

*Built with ❤️ for smarter link management* 
