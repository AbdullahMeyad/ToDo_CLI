# To-Do List CLI Application

A Command Line Interface (CLI) application for managing tasks in a multi-user environment, built using **Spring Boot**. Users can register, log in, and manage their personalized to-do lists.

## Features

- **User Authentication**
  - Register a new user.
  - Login with existing credentials.
- **Task Management**
  - Add tasks with titles and descriptions.
  - Update tasks (mark as completed or modify details).
  - Delete tasks.
  - View all tasks or filter by status (completed/pending).
- **Multi-User Support**
  - Each user has their own task list.
- **Persistence**
  - Data is stored in a relational database using JPA and Hibernate.

## Technologies Used

- **Backend:** Spring Boot
- **Database:** MySQL
- **Build Tool:** Maven
- **Security:** Spring Security
- **Logging:** SLF4J with Logback

## Prerequisites

To run this application, ensure you have:

- Java 17 or higher installed.
- Maven installed (if you are building the project manually).
- A terminal or command-line interface.

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/todo-cli-app.git
   cd todo-cli-app
   ```

2. **Build the Project**
   ```bash
   mvn clean install
   ```

3. **Run the Application**
   ```bash
   mvn spring-boot:run
   ```

4. **Interact with the CLI**
   Once the application starts, use the terminal to register, log in, and manage tasks.

## Usage

After starting the application, follow the on-screen prompts to:

1. **Register a New User**
   - Enter a unique username and password.
2. **Log In**
   - Use your registered credentials.
3. **Manage Tasks**
   - Commands:
     - `add` - Add a new task.
     - `list` - View all tasks.
     - `update` - Modify an existing task.
     - `delete` - Remove a task.
     - `logout` - Exit the current session.

## Future Enhancements

- Add Spring Security for enhanced authentication and role-based access.
- Introduce task priority and deadlines.
- Implement RESTful APIs for web or mobile integration.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
