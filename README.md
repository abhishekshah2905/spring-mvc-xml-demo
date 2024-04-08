# Spring MVC XML

This is a simple Spring MVC web application that demonstrates the use of XML configuration and annotations to create a controller and configure the application.

## Overview
This application is a basic example of a Spring MVC web application using XML configuration for the servlet and annotation-based controllers.

## Getting Started

### Prerequisites
- Java JDK 8 or higher
- Maven
### Installation
1. Clone the repository:
```bash
  git clone https://github.com/abhishekshah2905/spring-mvc-xml-demo.git
```
2. Navigate to the project directory:
```bash
  cd spring-mvc-xml-demo
```
3. Build the project:
```bash
  mvn clean install
```
4. Deploy the WAR file to a Servlet container (e.g., Apache Tomcat).

5. Access the application at http://localhost:8080

### Usage
- he HomeController handles requests to the root URL ("/") and adds a message to the model.
- The JSP view (index.jsp) in the WEB-INF/pages directory is used to render the response.

### Customization
- Modify the HomeController to handle different URLs or add more functionality.
- Update the view (index.jsp) to display different content or add additional pages.