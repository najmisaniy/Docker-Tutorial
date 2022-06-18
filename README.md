# Docker-Tutorial

## Operating System CSCI 3300 Section 1
## Term Paper Group 9
Group Members | Matric Number
--------------|--------------
 Muhammad Najmi Saniy Bin Mohd Nazul | (1823617)
 Afnan Iman bin Azman | (1920311)

### Table of Content

Docker Installation

### Introduction
Docker is an open source containerization platform. It enables developers to package applications into containers—standardized executable components combining application source code with the operating system (OS) libraries and dependencies required to run that code in any environment. Containers simplify delivery of distributed applications, and have become increasingly popular as organizations shift to cloud-native development and hybrid multicloud environments.

Developers can create containers without Docker, but the platform makes it easier, simpler, and safer to build, deploy and manage containers. Docker is essentially a toolkit that enables developers to build, deploy, run, update, and stop containers using simple commands and work-saving automation through a single API.

Docker also refers to Docker, Inc. (link resides outside IBM), the company that sells the commercial version of Docker, and to the Docker open source project (link resides outside IBM), to which Docker, Inc. and many other organizations and individuals contribute.


### Required Installation steps and procedures
1)Go to [Docker](https://www.docker.com/products/docker-desktop/) website and download installer for Windows

![Docker Page](Image/Docker Page.png)

## Setup phpMyAdmin and MySQL with Docker
1. Open cmd.exe by pressing “windows” button + “r” button
2. Type mkdir “PMA_docker” to make a phpmyadmin directory named PMA_docker
3. Type “cd PMA_docker’ to change directory to PMA_docker
![step3](Docker-Tutorial/Image/dockerPMAsetup/step3.png)
4. Type “code .” to create a new visual studio code in the directory
5. Press the new file icon
6. Name the file docker-compose.yml
7. Fill in the file with the following code:
8. Open xampp and start Apache and MySQL
9. Type “docker-compose up -d” to run service and wait for process to finish
10. Open localhost:8082 on your browser
11. Create new table named library
12. Insert column name, and length
13. Press “insert” button to insert data
14. Insert data and press “go”


###
###
