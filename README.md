<h2 align="center">🚀 Docker_Projects 🚀</h2>

<p align="center">
  This repository contains Dockerized projects that demonstrate the use of Docker for containerizing applications in different programming languages.
</p>

---

### **Java Project: Hello and Date Printer**

**Description:**  
This project is a simple Java application that prints "Hello" and the current date to the console.

**Purpose:**  
It demonstrates how to containerize a basic Java application using Docker, providing an example of how to package and deploy Java applications consistently across different environments.

**Dockerfile:**  
The Dockerfile is configured to compile and run the Java application within a Docker container.

---

### **Python Flask Project**

**Description:**  
This project is a web application built using the Python Flask framework. The application includes an API endpoint that returns a message indicating the server is up and running. Additionally, it features an aesthetically pleasing homepage with a navbar and well-styled content.

**Purpose:**  
It serves as an example of how to containerize a Python Flask web application using Docker, showcasing best practices for deploying web applications in a containerized environment.

**Dockerfile:**  
The Dockerfile is set up to install necessary dependencies, set environment variables, and run the Flask application within a Docker container.

---

### **Two-Tier Application Project**

**Description:**  
This project is a two-tier web application that combines a Python Flask-based web server and a MySQL database. The Flask application serves as the front-end, handling user requests, while the MySQL database serves as the back-end, managing data storage.

**Purpose:**  
It demonstrates how to design, build, and deploy a multi-container setup using Docker. The project showcases the separation of the front-end and back-end, emphasizing modularity and scalability in a containerized environment.

**Docker Setup:**  
The Docker setup includes a Docker Compose file that orchestrates the deployment of both containers. The Flask web server handles HTTP requests, and the MySQL database manages data persistence. The setup demonstrates how to manage inter-container communication and environment variables using Docker Compose.

---

### **Wanderlust: A Travel Blog Web Application**

**Description:**  
Wanderlust is a travel blog web application built with Python Flask. The app allows users to explore various travel destinations and share their experiences. It includes a homepage with blog posts, and features for users to interact with the content.

**Purpose:**  
This project demonstrates how to containerize a more complex web application using Docker. The setup includes a Dockerfile that configures the environment, installs dependencies, and exposes the Flask application on port 5000.

**Dockerfile:**  
The Dockerfile is configured to install the necessary libraries, set up the Flask app, and serve it on port 5000. The project also showcases how to handle static files and templates within a containerized environment.

---

<p align="center">
  ✨ Happy Coding! ✨
</p>
