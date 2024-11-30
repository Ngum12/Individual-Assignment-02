
# ALUFree Media: Connecting Students Through Social Sharing

## 🌟 Project Overview

ALUFree Media is an innovative social media platform designed specifically for students, providing a dynamic and interactive space to share, connect, and engage with content across academic and personal interests. Built with cutting-edge Flutter and Laravel technologies, our app empowers students to express themselves, collaborate, and build meaningful digital communities.

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Technologies](#-technologies-used)
- [Installation](#-installation-guide)
- [API Documentation](#-api-documentation)
- [Development Challenges](#-development-challenges)
- [Contributing](#-how-to-contribute)
- [License](#-licensing)

## ✨ Features

### Core Functionalities
- **User Authentication**: Secure registration and login
- **Content Posting**: Share photos, videos, and text updates
- **Interaction**: Like, comment, and share posts
- **Profile Management**: Customize user profiles
- **Real-time Notifications**: Instant updates on interactions

### Unique Student-Focused Features
- **Academic Content Sharing**: Ability to share study resources
- **Campus Event Announcements**
- **Interest-based Communities**
- **Anonymous Posting Options**

## 🚀 Technologies Used

### Frontend
- **Framework**: Flutter 3.10+
- **State Management**: Provider/Riverpod
- **UI Components**: Material Design
- **Navigation**: GoRouter

### Backend
- **Framework**: Laravel 9.0+
- **Authentication**: Laravel Sanctum
- **Database**: MySQL
- **API Development**: Laravel Resource Controllers

### Additional Technologies
- **Database**: MySQL
- **Hosting**: AWS/DigitalOcean
- **CI/CD**: GitHub Actions

## 💻 Installation Guide

### Prerequisites
- Flutter SDK 3.10+
- Dart 2.19+
- Laravel 9.0+
- Composer
- MySQL 8.0+

### Backend Setup (Laravel)

1. Clone the repository:
```bash
git clone https://github.com/yourusername/alufree-media-backend.git
cd alufree-media-backend
```

2. Install dependencies:
```bash
composer install
```

3. Configure environment:
```bash
cp .env.example .env
php artisan key:generate
```

4. Database configuration:
```bash
php artisan migrate
php artisan db:seed
```

### Frontend Setup (Flutter)

1. Clone the repository:
```bash
git clone https://github.com/yourusername/alufree-media-flutter.git
cd alufree-media-flutter
```

2. Get dependencies:
```bash
flutter pub get
```

3. Configure API endpoints:
- Edit `lib/config/api_config.dart`
- Add your backend URL and API keys

### Running the Application

**Backend**:
```bash
php artisan serve
```

**Frontend**:
```bash
flutter run
```

## 📡 API Documentation

### Authentication Endpoints

#### User Registration
- **Endpoint**: `/api/register`
- **Method**: POST
- **Request Body**:
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "securepassword"
}
```
- **Response**:
```json
{
  "user": {...},
  "token": "unique_authentication_token"
}
```

#### Create Post
- **Endpoint**: `/api/posts`
- **Method**: POST
- **Authentication**: Required
- **Request Body**:
```json
{
  "content": "Hello, ALUFree!",
  "media_url": "optional_media_link"
}
```

## 🛠 Development Challenges

### Challenge 1: Real-time Notifications
**Problem**: Implementing instant notifications
**Solution**: Utilized WebSockets with Laravel Echo and Flutter's socket_io_client

### Challenge 2: Cross-Platform UI Consistency
**Solution**: Developed custom widgets and used responsive design principles

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🎥 Demo

[🔗 YouTube Demo Video](https://youtube.com/your-demo-link)

## 📸 Screenshots

![Login Screen](/screenshots/login.png)
![Home Feed](/screenshots/home_feed.png)
![Profile Page](/screenshots/profile.png)

**© 2024 ALUFree Media. All Rights Reserved.**
