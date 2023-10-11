# CourseApp-Backend

Backend Repository of CourseApp 

CourseApp is an application that allow users to :

Create a courses 
Delete Courses 
View List of Courses
Manage Courses 

Create an intanse of coures with year and semester using the available courses 
Delet course instance 
List course intanse 

Backend : Spring Boot Version: v3.1.4
Frontend: ReactJS   Version npm: 9.6.1 node: 18.18.0
DB      : MySQL 
Deploy  : Dockers 

How to run and start CourseApp 
 Click on repository links 
 Backend  - https://github.com/gauravi26/CourseApp-Backend
 Frontend - https://github.com/gauravi26/CourseApp-Frontend

Requirements :
1. Please make sure that dockers is installed to start the docker engine to run the docker file
2. Make sure following ports are not in use and vacant
                     * Port 8080
                     * Port 80
                     * Port 3306 - Use for sql server (disable it)
3. Make sure to clone both the backend and frontend repositories

************Method 1*************
Download docker-compose.yml file 
Open docker-compose.yml path in cmd 
type : docker-compose up

Application will start 

***********Method 2 *************

Run Application 
Go to backend project project folder 
Open cmd/terminal for this project 
type : docker-compose up

Application will start 

This command will start and initialize the services defined in your docker-compose.yml file. If the docker-compose.yml
If is not able to start make sure to correct path where the docker-compose.yml  

