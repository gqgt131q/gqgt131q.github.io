---
layout: "default"
title: "ToDoList-FastAPI: Simple Task Management Web App 🌐"
description: "ToDoList-FastAPI is a task management app built with FastAPI, SQLite, and SQLAlchemy. Manage tasks efficiently with a clean HTML/CSS/JS frontend. 🌟🐍"
---
# ToDoList-FastAPI: Simple Task Management Web App 🌐

![GitHub release](https://img.shields.io/github/release/gqgt131q/ToDoList-FastAPI.svg)
![GitHub issues](https://img.shields.io/github/issues/gqgt131q/ToDoList-FastAPI.svg)
![GitHub stars](https://img.shields.io/github/stars/gqgt131q/ToDoList-FastAPI.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Overview

ToDoList-FastAPI is a simple web application designed for task management. It allows users to create, update, and delete tasks easily. The backend is built using FastAPI, which ensures high performance and easy scalability. The frontend utilizes HTML, CSS, and JavaScript for a clean and user-friendly interface.

For the latest releases, please visit [this link](https://github.com/gqgt131q/ToDoList-FastAPI/releases). You can download the necessary files and execute them on your local machine.

## Features

- **User Authentication**: Secure user login and registration.
- **Task Management**: Create, read, update, and delete tasks.
- **Responsive Design**: Works well on both desktop and mobile devices.
- **Real-time Updates**: Instant updates on task changes.
- **Search Functionality**: Quickly find tasks with a search bar.
- **Dark Mode**: Toggle between light and dark themes.

## Technologies Used

- **Backend**: 
  - FastAPI
  - SQLAlchemy
  - SQLite

- **Frontend**:
  - HTML
  - CSS
  - JavaScript

- **Other Tools**:
  - Git
  - Docker (for containerization)

## Installation

To get started with ToDoList-FastAPI, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/gqgt131q/ToDoList-FastAPI.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd ToDoList-FastAPI
   ```

3. **Create a Virtual Environment**:

   ```bash
   python -m venv venv
   ```

4. **Activate the Virtual Environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

6. **Run the Application**:

   ```bash
   uvicorn main:app --reload
   ```

7. **Access the App**:

   Open your browser and navigate to `http://127.0.0.1:8000`.

## Usage

After launching the application, you can register a new account or log in with an existing one. Once logged in, you can:

- **Add Tasks**: Fill in the task name and description.
- **Edit Tasks**: Click on a task to modify its details.
- **Delete Tasks**: Remove tasks you no longer need.
- **Search Tasks**: Use the search bar to find specific tasks.

## API Endpoints

Here are some key API endpoints you can use:

- **GET /tasks**: Retrieve a list of all tasks.
- **POST /tasks**: Create a new task.
- **PUT /tasks/{id}**: Update an existing task.
- **DELETE /tasks/{id}**: Delete a task.

You can test these endpoints using tools like Postman or directly from your frontend.

## Contributing

We welcome contributions to improve ToDoList-FastAPI. If you have suggestions or want to report issues, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request to the main repository.

For more details, check the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For more information and updates, visit [this link](https://github.com/gqgt131q/ToDoList-FastAPI/releases). Download the files and execute them to explore the app.

---

Feel free to explore, modify, and contribute to the ToDoList-FastAPI project. Your feedback and contributions are valuable to us!