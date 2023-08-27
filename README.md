# Gym mini Project

Welcome to the Gym Web PHP project! This project is designed to help you create a web application for managing a gym or fitness center. It's built using PHP, MySQL, and HTML/CSS, and provides features for both gym administrators and members.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
- [Usage](#usage)
  - [Admin Panel](#admin-panel)
  - [Member Portal](#member-portal)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Gym Web PHP project is a web-based application that aims to simplify gym management tasks, making it easier for both gym administrators and members to interact with the system. Administrators can manage memberships, schedule classes, track attendance, and more. Members can view class schedules, track their own attendance, and update their profiles.

## Features

- **Admin Panel:**
  - Manage members: Add, edit, and delete member profiles.
  - Manage memberships: Create and update membership plans.
  - Schedule classes: Set up classes, assign trainers, and define class times.
  - Track attendance: Mark attendance for classes and view attendance reports.
  
- **Member Portal:**
  - View class schedule: Check the schedule of upcoming classes.
  - Update profile: Members can update their personal information.
  - View attendance: See their attendance history for different classes.
  - Join classes: Members can enroll in classes they're interested in attending.

## Installation

Follow these steps to set up the Gym Web PHP project on your local development environment.

### Prerequisites

1. **Web Server:** You need a web server like Apache or Nginx installed.
2. **PHP:** Ensure you have PHP 7.x or later installed.
3. **MySQL:** Make sure you have MySQL or another compatible database system.
4. **Composer:** Install Composer, a PHP dependency management tool.

### Setup

1. **Clone the Repository:** Clone this repository to your web server's document root.

   ```bash
   git clone https://github.com/your-username/gym-web.git
   ```

2. **Install Dependencies:** Navigate to the project directory and install PHP dependencies using Composer.

   ```bash
   cd gym-web
   composer install
   ```

3. **Database Setup:** Create a new MySQL database for the project. Import the SQL schema from the `database.sql` file provided.

   ```bash
   mysql -u username -p database_name < database.sql
   ```

4. **Configuration:** Rename the `config.example.php` file to `config.php` and update the database credentials and other settings.

5. **Web Access:** Make sure your web server is correctly configured to serve the project. You may need to set up virtual hosts or configure your server's document root.

6. **Access the Project:** Open your web browser and navigate to the URL where the project is hosted.

## Usage

### Admin Panel

- Access the admin panel by logging in with your administrator credentials.
- Manage members, memberships, classes, and attendance using the provided interface.

### Member Portal

- Members can log in using their credentials.
- View class schedules, update their profiles, and see their attendance history.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

---
Outputs:
![Screenshot 2022-12-31 at 6 19 10 PM](https://user-images.githubusercontent.com/78723011/210137453-47dc0372-f2c5-4a81-add1-dbbf68c09b4f.png)
![Screenshot 2022-12-31 at 6 19 47 PM](https://user-images.githubusercontent.com/78723011/210137486-25696215-fae5-4762-986a-fc4be6e2f924.png)
![Screenshot 2022-12-31 at 6 19 55 PM](https://user-images.githubusercontent.com/78723011/210137511-091f0367-4973-4064-b3ea-54f8712d656c.png)
![Screenshot 2022-12-31 at 6 20 01 PM](https://user-images.githubusercontent.com/78723011/210137527-bb551ed7-708c-4ba2-a3ce-87dc70a60f9a.png)
![Screenshot 2022-12-31 at 6 20 06 PM](https://user-images.githubusercontent.com/78723011/210137548-7487ba53-e4ac-4ac4-8e39-cac0fc48dac1.png)
![Screenshot 2022-12-31 at 6 20 11 PM](https://user-images.githubusercontent.com/78723011/210137564-5be3289e-d38c-4dcd-b149-84fe0f35452d.png)
