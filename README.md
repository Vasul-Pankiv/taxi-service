[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Oswald&size=32&duration=3000&pause=&color=EAF747&vCenter=true&width=435&height=70&lines=Taxi+-+Service;Web+-+app)](https://git.io/typing-svg)
## Project description:
>This is a simple web application, as a learning project, realized in Java, based on SOLID principles, performs CRUD, authentication and registration operations. The main purpose of this application is to keep records of taxi service drivers and cars
## Project structure:
> This is an N-Tier Architecture
> * DAO - Data access Tier (CRUD methods)
> * Service - Business Tier
> * Controller - Presentation Tier
## :fire: Features:
> * :white_medium_small_square:registration a new driver
> * :white_medium_small_square:login / logout
> * :white_medium_small_square:create, update and remove all models
> * :white_medium_small_square:display list of all manufacturers, cars, drivers
## :wrench: Technologies:
> * :white_medium_small_square:MySQL
> * :white_medium_small_square:JDBC
> * :white_medium_small_square:Java 11
> * :white_medium_small_square:Maven
> * :white_medium_small_square:Tomcat
> * :white_medium_small_square:JSP
## How to launch the project on your PC:
> 1. Fork this repo
> 2. git clone \<your link>
> 3. Create schema and all tables using the file init_db.sql
> 4. Config ConnectionUtil.class  
> * private static final String URL = "URL";
> * private static final String USERNAME = "USERNAME";
> * private static final String PASSWORD = "PASSWORD";
> * private static final String JDBC_DRIVER = "JDBC_DRIVER";
> 5. Install [Tomcat](https://tomcat.apache.org/download-90.cgi)
> 6. Add Tomcat server to configuration
> 7. Run project
