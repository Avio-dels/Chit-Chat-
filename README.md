---

````markdown
# ChatApp

![GitHub repo size](https://img.shields.io/github/repo-size/Avio-dels/Chat-App)
![GitHub contributors](https://img.shields.io/github/contributors/Avio-dels/Chat-App)
![GitHub stars](https://img.shields.io/github/stars/Avio-dels/Chat-App?style=social)
![GitHub forks](https://img.shields.io/github/forks/Avio-dels/Chat-App?style=social)

A real-time chat application built with **PHP, MySQL, HTML, CSS, and JavaScript**, designed to be easy to set up locally using **XAMPP**. Users can communicate instantly in a simple, user-friendly interface.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Screenshots](#screenshots)

---

## Features

- Real-time messaging between users
- Multi-user support
- User-friendly and responsive interface
- File upload support (if implemented)
- Easy local setup with XAMPP

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache (via XAMPP)

---

## Installation and Setup

Follow these steps to run the ChatApp locally:

### 1. Clone the Repository
```bash
git clone https://github.com/Avio-dels/Chat-App.git
````

This will create a folder named `Chat-App` on your system.

### 2. Move to XAMPP

* Copy or move the cloned folder (`Chat-App`) to your **`htdocs`** folder
  *(Usually: `C:\xampp\htdocs\` on Windows)*
* Optionally, rename the folder to `chatapp` for simplicity.

### 3. Start XAMPP Services

* Open **XAMPP Control Panel**.
* Start **Apache** and **MySQL**.

### 4. Create the Database

* Open your browser and go to: `http://localhost/phpmyadmin/`
* Click **Databases → Create Database**.
* Name it `chatapp` and click **Create**.

### 5. Import SQL File

* Inside the cloned `Chat-App` folder, locate the SQL file (usually `chatapp.sql`).
* In phpMyAdmin, go to your `chatapp` database.
* Click **Import → Choose File → Select SQL file → Go**.

### 6. Run the Chat Application

* Open your browser and go to: `http://localhost/chatapp/`
* Your chat application is now ready to use.

---

## Usage

* Open multiple browser tabs or devices to test real-time chat.
* Type a message and hit send to communicate with other users.
* (Optional) Implement additional features like emojis, file sharing, or notifications.

---

## Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## License

This project is licensed under the **MIT License**.

---

## Screenshots

> You can add screenshots of your ChatApp here to make it visually appealing.

![ChatApp Screenshot](./screenshot1.png)
![ChatApp Screenshot](./screenshot2.png)

---

## Contact

For any questions or feedback, you can reach me via GitHub [@Avio-dels](https://github.com/Avio-dels).

````
