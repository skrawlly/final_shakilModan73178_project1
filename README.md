# Task 1 – Spring MVC Application

## Description
This is a simple Spring Boot application.
It has one controller and two GET endpoints.
---
## What was used  Used
- Java
- Spring Boot
- Spring Web
- Thymeleaf
- Maven
---
 Screenshot:  
![Greeting Page](screenshots/greeting_page.png)

---

## How Task it Works

1. The application is started from the main Spring Boot class.
   Spring Boot runs an embedded server and the application becomes available at `http://localhost:8080` which is standard.
2. The application contains one controller.
   The controller receives HTTP GET requests from the browser.
3. When the browser opens `http://localhost:8080`,
   a GET request is sent and the controller returns a simple text message that in this case is :Lorern ipsum dolor sit amet, consectrur...
   The text is displayed directly in the browser.

4. When the browser opens `http://localhost:8080/greeting`,
   a GET request is sent and the controller returns the name of an HTML file that i set it as greeting.html.
   Spring uses Thymeleaf to load this file and display it in the browser.

5. The HTML page shows a text message and an image loaded from static resources.

This project demonstrates basic Spring MVC functionality using controllers, views, and GET requests.

## Running the Application

Start the application from IntelliJ.
Open the browser and go to: the URL`http://localhost:8080/greeting` and then  the applications return an htmlpage in the browser
