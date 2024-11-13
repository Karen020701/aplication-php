**Hello World” project in PHP language**  
This is a basic project of a “Hello World” in PHP language, we are going to use Docker to create a container of the program and Railway is used to deploy the project in the cloud.  

It is required to verify the installation of the PHP extension on the computer, this is done by accessing to the computer and running the command php --version otherwise if you do not have it go to the page https://www.apachefriends.org/es/index.html and download the version of XAMPP that includes PHP.   

**Clone the project**  
Locate in a folder of preference to be able to clone the project with the following command:  
https://github.com/Karen020701/aplication-php.git  

To run the project locally, navigate to the project folder and run the command:  
php -S localhost:8080  
In the browser enter http://localhost:8080 and the message “Hello World php language” will be displayed.  

**Running with Docker**  
An image is built in Docker. Once inside the directory to download the created image the command is executed:  
docker pull karenchicaiza/aplicationphp  
To run the container the command is used:  
docker run -p 8080:8080 karenchicaiza/aplicationphp  

In the browser enter http://localhost:8080 and the message “Hello World php language” will be displayed.  


**Deployment on Railway**  
This project was deployed in Railway, the connection to the Railway account and access to the repository in Github was done.   
Once deployed I generate the link: https://aplication-php-production.up.railway.app/
