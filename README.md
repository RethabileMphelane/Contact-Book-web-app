# 📒 Contact Book Web App

A simple and functional **Contact Book** web application built using **HTML**, **CSS**, and **JavaScript** on the frontend, with a **MySQL** database on the backend. Users can add and store contact details including an avatar, and navigate easily between the form and home page.

## 🚀 Features

- Add new contacts with:
  - First name
  - Last name
  - Mobile number
  - Email address
  - Avatar (image upload)
- Clean and responsive user interface
- Submits data using JavaScript `fetch` API
- Communicates with a backend to store contacts in a MySQL database
- Navigation button to return to the home page

## 🛠️ Tech Stack

| Layer      | Technology        |
|------------|-------------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | PHP (via `insert-contact` endpoint) |
| Database   | MySQL             |

## 📂 Project Structure


## ⚙️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/contact-book.git
CREATE TABLE contacts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    firstname VARCHAR(50),
    lastname VARCHAR(50),
    mobile VARCHAR(20),
    email VARCHAR(100),
    avatar VARCHAR(255)
);

Let me know if you'd like the backend PHP code template or SQL file too.
