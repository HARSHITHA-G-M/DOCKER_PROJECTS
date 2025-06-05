title: "🐳 Docker Projects Collection"
description: >
  This repository contains a set of beginner-level Dockerized applications using different tech stacks like Python, Node.js, PHP, Java, and web servers like Nginx.
  Each folder is a standalone project showcasing how to containerize apps using Docker.

projects:
  - name: "Alpine-based"
    description: "A minimal container that prints 'Hello from Alpine!' using Alpine Linux."
    tech_stack: "Alpine Linux, Docker"
    commands:
      - "docker build -t alpine-hello ./Alpine-based"
      - "docker run alpine-hello"

  - name: "flask_app"
    description: "A simple Flask web application running inside a Docker container."
    tech_stack: "Python, Flask, Docker"
    commands:
      - "docker build -t flask-app ./flask_app"
      - "docker run -p 5000:5000 flask-app"
    url: "http://localhost:5000"

  - name: "hello_world"
    description: "A basic Hello World project that demonstrates a minimal Dockerfile setup."
    tech_stack: "Docker"
    commands:
      - "docker build -t hello-world ./hello_world"
      - "docker run hello-world"

  - name: "java_app"
    description: "A Java application containerized using Docker."
    tech_stack: "Java, Docker"
    commands:
      - "docker build -t java-app ./java_app"
      - "docker run java-app"

  - name: "nodejs_app"
    description: "A basic Node.js server running inside a container."
    tech_stack: "Node.js, Docker"
    commands:
      - "docker build -t node-app ./nodejs_app"
      - "docker run -p 3000:3000 node-app"
    url: "http://localhost:3000"

  - name: "php_app"
    description: "A PHP app served through Apache in Docker."
    tech_stack: "PHP, Apache, Docker"
    commands:
      - "docker build -t php-app ./php_app"
      - "docker run -p 8080:80 php-app"
    url: "http://localhost:8080"

  - name: "static_website_nginx"
    description: "A static HTML website hosted with Nginx in Docker."
    tech_stack: "HTML, CSS, Nginx, Docker"
    commands:
      - "docker build -t static-site ./static_website_nginx"
      - "docker run -p 8080:80 static-site"
    url: "http://localhost:8080"

usage:
  - "Clone the repository:"
  - "git clone https://github.com/your-username/your-repo-name.git"
  - "cd your-repo-name"
  - "Navigate into any folder and follow the build/run commands."

tools_used:
  - "Docker & Docker CLI"
  - "Flask / Node.js / PHP / Java"
  - "Nginx / Alpine Linux"
  - "VS Code / GitHub"

author:
  name: "Harshitha"
  github: "https://github.com/your-username"

license:
  type: "MIT License"
  file: "LICENSE"

