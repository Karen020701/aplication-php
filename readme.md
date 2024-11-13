# Hello World Project in PHP Language

This is a basic "Hello World" project in the PHP programming language. We will use Docker to create a container for the program, and Railway to deploy the project in the cloud.

## Prerequisites

It is required to verify the installation of the PHP extension on your computer. To check, open a terminal and run:

` php --version `

If PHP is not installed, you can download it by installing XAMPP, which includes PHP, from [https://www.apachefriends.org/es/index.html](https://www.apachefriends.org/es/index.html).

## Clone the Project

1. Locate a folder of your choice and clone the project with the following command:

    ` git clone https://github.com/Karen020701/aplication-php.git `

2. To run the project locally, navigate to the project folder and execute:

    ` php -S localhost:8080 `

3. Then, in your browser, go to [http://localhost:8080](http://localhost:8080). You should see the message: **"Hello World php language"**.

## Running with Docker

To run this project in a Docker container:

1. First, pull the Docker image. In the project directory, download the image with the command:

    ` docker pull karenchicaiza/aplicationphp `

2. To start the container, use the command:

    ` docker run -p 8080:8080 karenchicaiza/aplicationphp `

3. In your browser, go to [http://localhost:8080](http://localhost:8080) and you will see the message: **"Hello World php language"**.

## Deployment on Railway

This project has been deployed on Railway. The Railway account was connected, and access to the GitHub repository was configured. Once deployed, the following link was generated:

[https://aplication-php-production.up.railway.app/](https://aplication-php-production.up.railway.app/)


![image](https://github.com/user-attachments/assets/33dc86e5-a4fc-4ed3-8de4-85abe4ee18e9)
