# PHP Login Form 🐘

This project contains a simple PHP login form that allows users to enter their username and password. The form is built using PHP and styled with CSS. It can be easily deployed using Docker.

`version1` folder contains a html login form

`version2` folder contains the PHP form

## Features

- User-friendly interface for login.
- Basic form validation to ensure username and password fields are not empty.
- Displays submitted username and password for demonstration purposes (make sure to remove or secure this in a production environment).

## Requirements
- PHP 8.0 or higher
- Apache Web Server
- Docker (for containerization)

## Getting Started

1. Clone this repository: `git clone https://github.com/Azie88/PHP-Login-Form`

2. Build and Run with Docker: Make sure Docker is installed and running on your machine. Navigate to the `version2` folder and build the docker image: 

```
docker build -t php-login-form .
```

3. Run the Docker Container: Once the image is built, you can run a container from it. Use the following command to map port 800 on your host to port 80 on the container: 

```
docker run -p 800:80 php-login-form
```

4. Access the Application: Open your web browser and go to http://localhost:800 to view your PHP login form.

## Contributing

If you'd like to contribute to this project, please feel free to fork the repository and submit a pull request.

## Author

Andrew Obando

<a href="https://www.linkedin.com/in/andrewobando/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Andrew Obando | LinkedIn"/></a>
<a href="https://medium.com/@obandoandrew8">
![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)
</a>

---

Feel free to star ⭐ this repository if you find it helpful!