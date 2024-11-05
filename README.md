# kanban-board

## Description

This project enhances a pre-existing Kanban board application by incorporating secure authentication through JSON Web Tokens (JWT). The focus of this project is on implementing a robust login system, leveraging JWTs to validate and manage user sessions. By integrating JWTs, the application not only provides a secure login experience but also ensures that only authenticated users can access and interact with the Kanban board. This project highlights my ability to work with both front-end and back-end technologies to create secure, authenticated applications.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Demo](#demo)
- [Questions](#questions)

## Installation

To get started with the Kanban board application, clone the repository to your local machine and follow the steps below:

1. Clone the repository:
    ```
    git clone git@github.com:HappyPup1402/kanban-board.git
    ```

2. Navigate to the project directory:
    ```
    cd kanban-board/Develop
    ```

3. Install the required dependencies:
    ```
    npm install
    ```

4. Build the application:
    ```
    npm run build
    ```

5. Start the application:
    ```
    npm run start
    ```

Side note: to seed your database you will need to cd into the server folder and npm run build.

## Usage

Once the application is running, follow these steps to authenticate and interact with the Kanban board:

1. **Login**: Access the login page and enter your username and password. Upon successful login, a JWT will be generated and stored securely in the client’s local storage, allowing access to the Kanban board.

2. **Access Kanban Board**: After authentication, you'll be redirected to the main Kanban board page, where you can manage your tasks.

3. **Session Management**: The JWT is stored in local storage and will persist across page reloads. However, if you remain inactive for a set duration, your session will expire, and any subsequent action will redirect you back to the login page.

4. **Logout**: Logging out will clear the JWT from local storage, ensuring that the session is securely terminated.

## Features

- **JWT Authentication**: Secure login and session management with JSON Web Tokens.
- **Persistent Authentication**: The JWT is stored in local storage, allowing authenticated access across page reloads.
- **Session Expiry**: Inactivity for a defined period will invalidate the JWT, prompting a re-login for security.
- **Error Handling**: Invalid login attempts display an error message, ensuring clarity in the user experience.

## Demo

Check out the live demo: https://kanban-board-mbur.onrender.com

## Questions

If you have any questions about this project, feel free to reach out to me at [izaacramirez1402@gmail.com](mailto:izaacramirez1402@gmail.com) or visit my GitHub profile at [HappyPup1402](https://github.com/HappyPup1402).
