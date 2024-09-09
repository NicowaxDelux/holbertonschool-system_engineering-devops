# Web infrastructure design

This project focuses on designing various web infrastructure setups to understand concepts such as network basics, servers, web servers, DNS, load balancers, and monitoring. Each task involves designing a web infrastructure on a whiteboard and explaining the components involved.

## Concepts

- Network basics
- Live previews
- Server
- Web Server
- DNS
- Load balancer
- Monitoring

## Tasks
### 0. Simple web stack

#### Design a one server web infrastructure for www.foobar.com using:

    1 server
    1 web server (Nginx)
    1 application server
    1 application files (your code base)
    1 database (MySQL)
    Domain name foobar.com configured with a www record pointing to server IP 8.8.8.8

### Diagram

<img src="" alt="App Screenshot" with="800">

### 1. Distributed web infrastructure

#### Design a three server web infrastructure for www.foobar.com with:

    2 servers
    1 web server (Nginx)
    1 application server
    1 load-balancer (HAproxy)
    1 set of application files (your code base)
    1 database (MySQL)

### Graphic

<img src="" alt="App Screenshot" width="800">

### 2. Secured and monitored web infrastructure

#### Design a three server web infrastructure for www.foobar.com with security, encryption, and monitoring:

- 3 firewalls
- SSL certificate for HTTPS
- 3 monitoring clients
- Terminate SSL at the load balancer level
- Implement MySQL Primary-Replica cluster

### Graphic

<img src="" alt="App Screenshot" width="800">

### 3. Scale up

#### Discuss the differences between application server and web server and design an infrastructure with:

- 1 server
- 1 load-balancer (HAproxy) configured as a cluster with another one
- Split components (web server, application server, database) on their own servers

### Graphic

<img src="" alt="App Screenshot" width="800">

## Authors

<p style="text-align: center;"><strong><big>Nicolas Rondon</big></strong></p>

<div style="text-align: center;">
    <a href="">
        <img src="https://github.com/camilof91/imagenes/blob/master/icons-linkedin.png?raw=true" style="display: inline-block; margin-right: 20px; vertical-align: middle;" width="60">
    </a>
    <a href="">
        <img src="https://github.com/camilof91/imagenes/blob/master/big-%20GitHub-logo.png?raw=true" style="display: inline-block; vertical-align: middle;" width="100">
    </a>
</div>

<p style="text-align: center;"><strong><big>Maria Alejandra Gonzalez</big></strong></p>

<div style="text-align: center;">
    <a href="https://www.linkedin.com/in/maria-alejandra-gonzalez-londo%C3%B1o-a5084a208?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
        <img src="https://github.com/camilof91/imagenes/blob/master/icons-linkedin.png?raw=true" style="display: inline-block; margin-right: 20px; vertical-align: middle;" width="60">
    </a>
    <a href="https://github.com/marialegl">
        <img src="https://github.com/camilof91/imagenes/blob/master/big-%20GitHub-logo.png?raw=true" style="display: inline-block; vertical-align: middle;" width="100">
    </a>
</div>

<p style="text-align: center;"><strong><big>Vanessa Requejo</big></strong></p>

<div style="text-align: center;">
    <a href="https://www.linkedin.com/in/camilo-fetecua">
        <img src="https://github.com/camilof91/imagenes/blob/master/icons-linkedin.png?raw=true" style="display: inline-block; margin-right: 20px; vertical-align: middle;" width="60">
    </a>
    <a href="https://github.com/camilof91">
        <img src="https://github.com/camilof91/imagenes/blob/master/big-%20GitHub-logo.png?raw=true" style="display: inline-block; vertical-align: middle;" width="100">
    </a>
</div>