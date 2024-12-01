<div align="center">
  <img src="https://raw.githubusercontent.com/yourusername/ALUFreeMedia/main/assets/logo.png" width="200" alt="ALUFree Media Logo">
  
  # ALUFree Media 📱✨
  
  [![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
  [![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
  [![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
  
  **Empowering Student Connections, One Post at a Time** 🌐📚
</div>

## 🎯 Project Vision

ALUFree Media is a revolutionary social platform designed exclusively for students, bridging academic and social worlds through seamless, intuitive digital interaction. More than just a social media app, we're creating a vibrant ecosystem where knowledge sharing, collaboration, and community building happen effortlessly.

## 🖼️ Visual Showcase

<div align="center">
  <img src="https://raw.githubusercontent.com/yourusername/ALUFreeMedia/main/screenshots/app-mockup.png" width="800" alt="ALUFree Media App Mockup">
  
  ### [🎥 Watch Full Demo Video](https://drive.google.com/file/d/1NX8opL7D27PsNzm-WT7Ewrad3xtETGWU/view?usp=sharing)
</div>

## 📋 Table of Contents

- [🎯 Project Vision](#-project-vision)
- [🖼️ Visual Showcase](#-visual-showcase)
- [✨ Key Features](#-key-features)
- [🚀 Technologies](#-technologies)
- [💻 Installation Guide](#-installation-guide)
- [📡 API Documentation](#-api-documentation)
- [🛠 Development Insights](#-development-insights)
- [🤝 Contributing](#-contributing)
- [📄 Licensing](#-licensing)

## ✨ Key Features

### 🌟 Core Functionalities
- **Seamless Authentication**: Secure, one-tap student login
- **Rich Content Sharing**: Post text, images, videos, and documents
- **Interactive Engagement**: Like, comment, and share with ease
- **Smart Notifications**: Real-time updates and interactions

### 🎓 Student-Centric Innovations
- **Academic Resource Hub**: Share study materials, notes, and insights
- **Campus Event Discoveries**: Local and virtual event announcements
- **Interest-Based Communities**: Connect with like-minded peers
- **Anonymous Posting Option**: Share candidly when needed

## 🚀 Technologies

<div align="center">
  <img src="https://img.icons8.com/fluency/48/flutter.png" alt="Flutter" width="50"/>
  <img src="https://img.icons8.com/fluency/48/laravel.png" alt="Laravel" width="50"/>
  <img src="https://img.icons8.com/color/48/mysql-logo.png" alt="MySQL" width="50"/>
  <img src="https://img.icons8.com/color/48/firebase.png" alt="Firebase" width="50"/>
</div>

### Frontend
- **Framework**: Flutter 3.10+
- **State Management**: Provider/Riverpod
- **UI Components**: Material Design

### Backend
- **Framework**: Laravel 9.0+
- **Authentication**: Laravel Sanctum
- **Database**: MySQL 8.0+

## 💻 Installation Guide

> 🔧 **Prerequisites**
> - Flutter SDK 3.10+
> - Dart 2.19+
> - Composer
> - MySQL 8.0+

### Backend Setup (Laravel)

```bash
# Clone Repository
git clone https://github.com/yourusername/alufree-media-backend.git
cd alufree-media-backend

# Install Dependencies
composer install

# Configure Environment
cp .env.example .env
php artisan key:generate

# Database Migration
php artisan migrate
php artisan db:seed
```

### Frontend Setup (Flutter)

```bash
# Clone Repository
git clone https://github.com/yourusername/alufree-media-flutter.git
cd alufree-media-flutter

# Get Dependencies
flutter pub get

# Run Application
flutter run
```

## 📡 API Endpoints

| Endpoint | Method | Description | Authentication |
|----------|--------|-------------|----------------|
| `/api/register` | POST | User Registration | None |
| `/api/login` | POST | User Authentication | None |
| `/api/posts` | GET/POST | Create/Retrieve Posts | Required |
| `/api/posts/{id}/interact` | POST | Like/Comment | Required |

### Sample Authentication Request

```json
{
  "email": "student@university.edu",
  "password": "secure_password_2024"
}
```

## 🛠 Development Challenges

> 🧩 **Challenge**: Real-time Notification System
> 
> **Solution**: Implemented WebSocket communication using Laravel Echo and Flutter's socket_io_client, ensuring instant, seamless notifications across platforms.

> 🎨 **Challenge**: Cross-Platform UI Consistency
> 
> **Solution**: Developed responsive, adaptive custom widgets with Flutter, maintaining design integrity across iOS and Android.

## 🤝 Contributing

1. Fork the Repository
2. Create Feature Branch (`git checkout -b feature/amazing-feature`)
3. Commit Changes (`git commit -m 'Add Amazing Feature'`)
4. Push to Branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 Licensing

Distributed under the **MIT License**. 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

<div align="center">
  **Crafted with ❤️ by Student Developers**
  
  [GitHub Repository](https://github.com/Ngum12/Individual-Assignment-02?tab=readme-ov-file)
</div>
