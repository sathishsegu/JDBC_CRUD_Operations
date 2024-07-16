# JDBC_CRUD_Operations

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#SetupandInstallation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)



## About the Project

This project demonstrates CRUD (Create, Read, Update, Delete) operations using JDBC in Java. The application interacts with a MySQL database to perform basic database operations on a `student` table.



## Features

- **Insert**: Add new student records.
- **Update**: Modify existing student records.
- **Delete**: Remove student records.
- **View**: Display all student records.



## Technologies Used

- Java
- JDBC
- MySQL
- JDBC Driver class API
- Eclipse



## Getting Started

To get a local copy up and running, follow these steps.


### Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL database
- JDBC Driver for MySQL

### Setup and Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/JavaJDBC-CRUD-Operations.git
   cd JavaJDBC-CRUD-Operations

2. **Create the MySQL Database**
   CREATE DATABASE kodnest;
    USE kodnest;
    CREATE TABLE student (
        id INT PRIMARY KEY,
        name VARCHAR(50)
    );

3. **Update Database Credentials**
    String url = "jdbc:mysql://localhost/kodnest";
    String uName = "root";
    String pwd = "your_password";


4. **Compile and run the application**
    javac -d bin src/com/kodnest/mysql/*.java
    java -cp bin com.kodnest.mysql.Application



## Usage
1. Start the application:
   - Run the main class Application.java.
   - Follow the prompts to insert, update, delete, or view student records.
  
   
2. Application Menu:
     Application Started.....
      1. Insert the record
      2. Update the record
      3. Delete the record
      4. Exit
      Enter an option to execute DB operations: 



## Contributing

Contributions are what make the open source community such an amazing place to be, learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/your-feature`)
3. Commit your Changes (`git commit -m 'Add some feature'`)
4. Push to the Branch (`git push origin feature/your-feature`)
5. Open a Pull Request


## License

This project is for personal or educational use only. It cannot be sold or used by others without permission. See the [LICENSE](LICENSE.md) file for details.

## Contact
For any inquiries or support, please reach out through the following channels
sathishsegu123@gmail.com
[LinkedIn](https://www.linkedin.com/in/sathishkumarsegu/)

Project Link: [https://github.com/sathishsegu/tunetastic](https://github.com/sathishsegu/JDBC_CRUD_Operations)



