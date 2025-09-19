# java--project

# Employee Management System 🧑‍💼

A simple desktop-based application built with Java Swing to manage employee information. This project aims to provide a user-friendly graphical interface for handling basic employee data operations.

---

## 🌟 Current Features

This is the initial version of the project. The current features include:

* **Animated Splash Screen:** A welcoming GIF splash screen is displayed for 5 seconds when the application starts.
* **Login Window:** After the splash screen, the application transitions to a login screen (the `login` class needs to be implemented).

---

## 🛠️ Technologies Used

* **Language:** Java
* **GUI Framework:** Java Swing
* **IDE:** Can be run from any standard Java IDE (e.g., Eclipse, IntelliJ, VS Code).

---

## 🚀 Getting Started

Follow these steps to get the project running on your local machine.

### Prerequisites

* **Java Development Kit (JDK):** Make sure you have JDK 8 or a newer version installed.
* An IDE that supports Java projects.

### Project Structure
Ensure your project has an `icons` folder inside your source path (e.g., inside the `src` folder) and that the `front.gif` file is placed inside it. The code uses `ClassLoader.getSystemResource()` to find this file.

---

src
└── icons
└── front.gif
└── employee
└── management
└── system
├── splash.java
└── login.java

---

## 🏃 How to Run the Application

1.  Navigate to the `splash.java` file.
2.  Run the `main(String[] args)` method.
3.  The application will launch, displaying the splash screen first and then proceeding to the login window.
