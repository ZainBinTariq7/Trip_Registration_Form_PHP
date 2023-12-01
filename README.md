# Overview
This project consists of a simple web form designed to collect participant information for a trip to the USA. Users can input details such as their name, age, gender, email, phone number, and additional information.

## Getting Started
To use this project, follow these steps:

### Clone the Repository:
- git clone [repository-url]


### Database Configuration:
- Set up your database by configuring the connection variables in the PHP code (index.php). Update the values for $server, $username, and $password according to your database setup.

### Web Server:
- Deploy the project on a web server like Apache or Nginx.


### Access the Form:
- Open your web browser and navigate to the project's URL.

## Project Structure
- `index.php:` Main PHP file containing the form handling and database interaction logic.
- `style.css:` CSS file for styling the HTML form.

## Database Schema
The project assumes a database named trip and a table named trip with fields name, age, gender, email, phone, other, and dt for storing participant information.


- CREATE TABLE `trip` (
  `name` VARCHAR(255),
  `age` INT,
  `gender` VARCHAR(10),
  `email` VARCHAR(255),
  `phone` VARCHAR(15),
  `other` TEXT,
  `dt` TIMESTAMP );

## Usage
Fill out the form with your details.
Click the "Submit" button.
Check for a confirmation message indicating successful form submission.

## Contributing
If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature/your-feature).
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature/your-feature).
- Open a pull request.
