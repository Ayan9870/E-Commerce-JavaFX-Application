# E-Commerce JavaFX Application

---

## Project Overview

Designed and developed a comprehensive JavaFX desktop application for restaurant order management, featuring robust user authentication, dynamic menu handling, and real-time order tracking. The application allows staff to log in securely, manage table orders, update item availability, and monitor order status from placement to fulfillment, streamlining in-house operations with an intuitive and interactive interface.

---

## Access to Code 🔒

The source code for this project is **private** and available upon request.

If you're an **employer** or **recruiter** and would like to review the code, please **request access via email** at **ayanhashmi205@yahoo.com**.

---

## Installation 📦

### Prerequisites
- **Java Development Kit (JDK) 11 or higher**
- **JavaFX SDK 11 or higher**
- **IDE with JavaFX support** (IntelliJ IDEA, Eclipse, or NetBeans)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/ayanhashmi/restaurant-order-management.git
   cd restaurant-order-management
   ```

2. **Setup JavaFX in your IDE**
   - Download JavaFX SDK from [OpenJFX](https://openjfx.io/)
   - Extract and configure module path in your IDE
   - Add VM options: `--module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.base,javafx.fxml`

3. **Run the application**
   - Open the project in your IDE
   - Run `Main.java`
   - The SQLite database (`application.db`) will be created automatically on first run

### Manual Compilation (Optional)
```bash
javac --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.base,javafx.fxml -cp . *.java
java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.base,javafx.fxml Main
```

---

## Features 📋

### Authentication & User Management
* **User Registration** - Create new accounts with secure signup process
* **User Login** - Secure authentication with username/password
* **Profile Management** - View and edit personal information
* **Profile Editing** - Update user details with persistent storage

### Order Management System
* **Add Orders** - Place new food orders with customizable quantities
* **Shopping Basket** - Real-time basket management with item modification
* **Order Modification** - Change existing orders before processing
* **Order History** - Comprehensive view of all placed orders
* **Order Status Tracking** - Real-time status updates and monitoring

### Food Service Features
* **Menu Selection** - Browse available food items
* **Quantity Control** - Customize quantities for each item type
* **Order Calculation** - Automatic total calculation and pricing
* **Order Processing** - Complete order workflow from selection to confirmation

### Payment & Billing
* **Payment Processing** - Secure payment handling system
* **Transaction Management** - Complete payment workflow
* **Order Confirmation** - Receipt generation and confirmation

### Administrative Features
* **Sales Reporting** - Generate comprehensive sales reports
* **Order Analytics** - Track order patterns and statistics
* **Data Export** - Export order data for analysis

### Technical Features
* **Data Persistence** - SQLite database for reliable data storage
* **Real-time Updates** - Live UI updates with JavaFX properties
* **MVC Architecture** - Clean separation of concerns
* **Error Handling** - Comprehensive validation and user feedback

---

## Technology Stack 🔧

### Frontend
* **JavaFX** - Modern desktop GUI framework
* **FXML** - Declarative UI layout with Scene Builder integration
* **CSS** - Custom styling and theming

### Backend
* **Java** - Object-oriented programming with MVC architecture
* **SQLite** - Lightweight, file-based database (no installation required)
* **JDBC** - Database connectivity and operations
* **DAO Pattern** - Clean data access layer abstraction

### Architecture
* **Model-View-Controller (MVC)** - Separation of concerns
* **Observer Pattern** - JavaFX ObservableList for UI data binding
* **Factory Pattern** - Database connection management

---

## How to Use 🚀

### Getting Started
1. **First Time Setup**
   - Run the application by executing `Main.java`
   - The application will automatically create the SQLite database
   - You'll be presented with the login screen

2. **User Registration**
   - Click "Sign Up" on the login screen
   - Fill in your personal details (first name, last name, username, password)
   - Submit the form to create your account
   - Return to login screen to access your account

3. **User Authentication**
   - Enter your username and password
   - Click "Login" to access the main application

### Main Application Workflow

4. **Dashboard Navigation**
   - Access the home dashboard after login
   - View your profile information
   - Navigate to different sections using the menu

5. **Managing Your Profile**
   - View your profile details in the Profile section
   - Edit your information using the Edit Profile feature
   - Save changes to update your account

6. **Placing Orders**
   - Navigate to the "Add Order" section
   - Select food items and specify quantities
   - Add items to your shopping basket
   - Review your order in the Shopping Basket
   - Proceed to payment when ready

7. **Payment Processing**
   - Review your order total
   - Enter payment information
   - Complete the transaction
   - Receive order confirmation

8. **Order Management**
   - View all your orders in the order history
   - Modify existing orders using "Change Order"
   - Track order status and details

9. **Sales Analytics**
   - Access sales reports for business insights
   - View order trends and statistics

---

## Author ✨

| <a href="https://github.com/ayan9870" target="_blank">**Muhammad Ayan Hashmi**</a> |
|:--:|
| ![Ayan Hashmi](https://github.com/ayan9870.png?size=100) |
| [`github.com/ayan9870`](https://github.com/ayan9870) |

---

## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
