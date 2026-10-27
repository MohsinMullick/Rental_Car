# Rental Car

A web-based car and bike rental management system built with PHP, MySQL, HTML and CSS.

## Features

- Customer registration, login and profile management
- Browse vehicles by type: Sedan, SUV, Mini Van and Bike
- Vehicle booking and payment
- Feedback and ride request submission
- Admin dashboard to manage customers, workers, vehicles and bookings
- Worker login and dashboard

## Tech Stack

| Layer    | Technology  |
|----------|-------------|
| Frontend | HTML, CSS   |
| Backend  | PHP         |
| Database | MySQL       |
| Server   | Apache (XAMPP) |

## Screenshots

<!-- Screenshot upload korar por nicher line gulo uncomment kore naam thik koro -->
<!-- ![Home](screenshots/home.png) -->
<!-- ![Booking](screenshots/booking.png) -->
<!-- ![Admin Dashboard](screenshots/admin.png) -->

## Getting Started

### Requirements
- XAMPP (or any Apache + PHP + MySQL setup)
- A web browser

### Installation

1. Clone the repository into your web server folder:
   ```bash
   cd C:\xampp\htdocs
   git clone https://github.com/MohsinMullick/Rental_Car.git
   ```
2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Open `http://localhost/phpmyadmin`, create a new database and import the `database.sql` file.
4. Open `connect.php` and set your database name, username and password.
5. Visit `http://localhost/Rental_Car/` in your browser.

## Project Structure

| File                        | Purpose                      |
|-----------------------------|------------------------------|
| `connect.php`               | Database connection          |
| `Customer*.php`             | Customer management pages    |
| `Worker*.php`               | Worker management pages      |
| `Admin*.php`                | Admin login and dashboard    |
| `Car_*.php`, `Bike.php`     | Vehicle listing pages        |
| `Booking.php`, `Payment.php`| Booking and payment          |
| `Feedback.html`             | Customer feedback form       |

## Author

**Mohsin Mullik**
GitHub: [@MohsinMullick](https://github.com/MohsinMullick)
