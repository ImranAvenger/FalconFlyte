# FalconFlyte

FalconFlyte is a web-based chat application developed as part of the Web Engineering Lab course. It facilitates real-time communication among users, featuring user authentication, real-time messaging, and user search functionalities.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **User Authentication:**
  - Sign up and create a new account
  - Log in with existing credentials
  - Log out to end the session

- **Real-time Chat:**
  - Send and receive messages in real-time
  - View chat history

- **User Management:**
  - Display a list of users available for chat
  - Search for users within the chat application

## Technologies Used

- **Front-end:**
  - HTML
  - CSS
  - JavaScript

- **Back-end:**
  - PHP
  - SQL

## Project Structure
```
.
└── FalconFlyte/
    ├── LICENSE
    ├── README.md
    ├── chat.php
    ├── header.php
    ├── index.php
    ├── login.php
    ├── query.sql
    ├── style.css
    ├── users.php
    ├── javascript/
    │   ├── chat.js
    │   ├── login.js
    │   ├── pass-show-hide.js
    │   ├── signup.js
    │   └── users.js
    └── php/
        ├── config.php
        ├── data.php
        ├── get-chat.php
        ├── insert-chat.php
        ├── login.php
        ├── logout.php
        ├── search.php
        ├── signup.php
        ├── users.php
        └── images/
            ├── logo.png
            └── background.jpg
```




## Installation

- Clone the repository:

        git clone https://github.com/your-username/FalconFlyte.git


- Navigate to the project directory:

        cd FalconFlyte



- Set up the database:
    - Create a MySQL database named `chatapp`.
    - Import the `query.sql` file into the `chatapp` database.

- Configure the database connection:
    - Open `php/config.php` and update the database credentials.

## Usage

- Start your local server (e.g., using XAMPP or WAMP).
- Navigate to the project directory in your web browser:

        http://localhost/FalconFlyte


- Sign up for a new account or log in with existing credentials.
- Start chatting with other users in real-time!

## Contributing

- Contributions are welcome! Please follow these steps to contribute:

    - Fork the repository.
    - Create a new branch:

            git checkout -b feature/YourFeature


    - Make your changes.
    - Commit your changes:

            git commit -m "Add YourFeature"



    - Push to the branch:

          git push origin feature/YourFeature


    - Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the Web Engineering Lab course instructors for their guidance and support throughout the development of this project.
