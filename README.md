# Koshkat - Admin E-commerce Application

![Koshkat Logo](link-to-logo.png) <!-- قم بإضافة رابط لشعار التطبيق إذا كان متوفرًا -->

## Overview
**Koshkat** is an admin application built with Flutter for managing an e-commerce solution focused on pet products, specifically for cats. This app provides an easy-to-use interface that allows admin users to manage their product catalog, view sales, and maintain order details.

## Features
- **Login Authentication**: Users log in securely using Firebase authentication.
- **Order Management**: View a list of customer orders, check details, and update statuses as necessary.
- **Product Management**:
  - **Add New Products**: Add new products with details like name, description, price, and images.
  - **Edit Existing Products**: Update product information, prices, stock levels, and images.
  - **Multi-language Support**: Using Easy Localization, the app supports both English and Arabic languages for seamless user experience.
- **Sales Overview**: Provides insights and an overview of total sales, orders, and active listings.

## Screens
1. **Login Screen**: Allows admin users to log in with email and password.
2. **Order Screen**: Displays a list of orders and individual order details.
3. **Product Management Screen**: Interface to add new products, edit existing products, and delete products if needed.
4. **Sales Dashboard**: Provides statistics on sales, revenue, and active products.

## Tech Stack
- **Flutter**: Used for building the UI and ensuring a responsive and consistent user experience across different devices.
- **Firebase**:
  - **Authentication**: For secure user login.
  - **Firestore**: To store and retrieve data for products, orders, and user profiles.
  - **Firebase Remote Config**: Configurable settings for managing app parameters and URLs.
- **State Management**: Implemented using Flutter Bloc (Cubit) for organized and maintainable state handling.
- **Localization**: Easy Localization package used for supporting both English and Arabic languages.

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/koshkat.git
   cd koshkat
