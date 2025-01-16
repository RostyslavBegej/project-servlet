# Project Servlet

## Overview

__Project Servlet__ is a Java-based web application built using Servlets. This project demonstrates the core functionalities of Servlet programming, including handling HTTP requests and responses, as well as managing session data in a web application.

## Features

- __HTTP Request Handling__: Handle HTTP GET and POST requests.
- __Session Management__: Maintain session data across multiple requests from the same client.
- __Servlet Configuration__: Configure servlets using the **`web.xml`** deployment descriptor.
- __Basic User Interface__: Simple user interface for interaction (optional or can be expanded).


## Requirements

Before running this project, ensure you have the following installed:

- __JDK 8 or higher__: Java Development Kit to compile and run the project.
- __Apache Tomcat 8.0 or higher__: Servlet container to deploy and run the project.
- __Maven__: For building and managing dependencies (optional if using an IDE that supports Maven).

## Getting Started

### Clone the repository:

```bash
git clone https://github.com/RostyslavBegej/project-servlet
```

### Build the project:
1. Navigate to the project directory:

```bash
cd project-servlet
```

2. Build the project using Maven (if applicable):

```bash
mvn clean install
```

### Deploy to Apache Tomcat:

1. Copy the generated **`.war`** file (located in **`target/`**) to the **`webapps`** directory of your Tomcat server.
2. Start the Tomcat server.
3. Visit **`http://localhost:8080/your-war-file-name`** in your web browser to access the application.

## Usage

1. Once deployed, the application will handle HTTP requests based on the servlet mappings defined in the web.xml file.
2. You can modify the servlets to add specific functionality, such as user login, registration, or data processing.
3. You can also test the servlets locally by sending HTTP requests using tools like Postman or curl.
