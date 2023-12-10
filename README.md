# Security System

## Overview
This C++ program implements a basic security system with features like user registration, login, and password change. Users interact with the system through a console-based interface. The program uses file handling to store user information, including usernames and passwords.

## Table of Contents
1. [Features](#features)
2. [Usage](#usage)
3. [Code Structure](#code-structure)
4. [Improvements](#improvements)
5. [Security Considerations](#security-considerations)
6. [Contributing](#contributing)
7. [License](#license)

## Features <a name="features"></a>
- **User Registration:** Allows users to register by providing a username, password, and age.
- **Login:** Users can log in with their registered username and password.
- **Password Change:** Provides the option to change the password after verifying the old password.
- **File Handling:** Utilizes file I/O to store and retrieve user information.

## Usage <a name="usage"></a>
1. **Compile the Code:**
   ```bash
   g++ security_system.cpp -o security_system
