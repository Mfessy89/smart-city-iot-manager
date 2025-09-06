# smart-city-iot-manager
Python project for Smart City IoT Device Manager with user registration and login.”
## Features

- **User Registration**  
  - Secure username (must contain `_` and max 8 characters)  
  - Strong password rules (minimum 10 characters, includes number, capital letter, and special character)  
  - Captures first name, last name, role, and department  

- **User Login**  
  - Verifies credentials  
  - Displays personalized greeting with role and department  

- **System Info**  
  - Shows the number of registered users  

- **Menu-driven interface**  
  - Easy-to-use console menu with options to register, login, view system info, or exit  

---

## Roles and Departments

- **Roles:**  
  - City Administrator  
  - IoT Technician  
  - Data Analyst  

- **Departments:**  
  - Traffic Management  
  - Environmental Monitoring  
  - Public Safety  
  - Infrastructure Maintenance  

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOURUSERNAME/smart-city-iot-manager.git
Navigate to the project folder:

bash
Copy code
cd smart-city-iot-manager
Run the Python script:

bash
Copy code
python smart_city_iot_manager.py
Follow the on-screen menu to register, login, or view system info.

Screenshots
(Optional: Add screenshots of your program in action here)

Skills Demonstrated
Python programming: functions, loops, dictionaries, conditionals

Input validation and string handling (.strip(), password rules)

Menu-driven console interface

Basic system management logic

Future Improvements
Store user data in a database for persistence

Add password hashing for security

Implement a GUI for a more user-friendly interface

Integrate with actual IoT devices for real-world Smart City applications

License
This project is open-source and available for learning purposes.
