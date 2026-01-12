# Flash News Management System

A web-based Flash News Management System developed for departmental communication.  
Users can securely log in, post flash news, preview upcoming events, filter news by date ranges, edit entries, and download daily reports.

---

## Features

- Session-based authentication (secure login required)
- Post flash news with event date and time
- Preview upcoming news with filters:
  - Next 3 days
  - Next 1 month
  - Custom date range
- Edit existing flash news entries
- View flash news by selected date
- Download daily flash news as text file
- Modern responsive UI with fixed headers and navigation

---

## Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript

**Backend**
- PHP (Session handling, CRUD operations)

**Database**
- MySQL

---

## Project Structure

FLASHNEWS/
|-- login.php
|-- dashboard.php
|-- submit_flashnews.php
|-- preview_flashnews.php
|-- edit_flashnews.php
|-- get_news_by_date.php
|-- logout.php
|
|-- images/
| |-- logo-left.png
| -- logo-right.jpg | -- database/
`-- flashnews_db.sql

---


---

## Database Schema

**Database Name:** `flashnews_db`

**Table:** `flash_news`

| Column Name     | Type         | Description |
|-----------------|--------------|-------------|
| id              | INT (PK)     | Auto Increment ID |
| userid          | VARCHAR      | User ID from session |
| username        | VARCHAR      | Username |
| department      | VARCHAR      | Department name |
| message         | TEXT         | Flash news content |
| event_date      | DATE         | Event date |
| event_time      | TIME         | Event time |
| sent_timestamp  | TIMESTAMP    | Auto submission time |

---

## Installation & Setup

### 1. Clone the Repository
git clone https://github.com/Piritha-15/FLASHNEWS.git


### 2. Move to XAMPP / WAMP directory

### 3. Import Database
- Open phpMyAdmin  
- Create database: `flashnews_db`  
- Import `database/flashnews_db.sql`

### 4. Start Server
- Start Apache and MySQL in XAMPP
- Open in browser:
http://localhost/FLASHNEWS/login.php


---

## Usage Flow

1. Login with valid credentials
2. Submit flash news
3. Preview upcoming news
4. Filter by date range
5. Edit existing entries if needed
6. View news by specific date
7. Download daily report

---

## UI Highlights

- Gradient institutional header
- Fixed navigation bar
- Clean card-based flash news display
- Date filtering interface
- Responsive layout

---

## Future Enhancements

- Role-based access (Admin / User)
- PDF and CSV export
- Delete flash news option
- Email notification for upcoming events
- Mobile-first responsive optimization

---

## Author

**Piritha N**  
Computer Science Undergraduate  
Full Stack Development (PHP, MySQL, HTML, CSS)

GitHub: https://github.com/Piritha-15

---

## License

This project is for academic and internal organizational use.

