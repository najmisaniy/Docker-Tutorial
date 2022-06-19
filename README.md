# Docker-Tutorial

## Operating System CSCI 3300 Section 1
## Term Paper Group 9
Group Members | Matric Number
--------------|--------------
 Muhammad Najmi Saniy Bin Mohd Nazul | (1823617)
 Afnan Iman Bin Azman | (1920311)
 Mohamad Amir Syakirin Bin Shafie | (1826571)

### Table of Content

Docker Installation

## Introduction
Docker is an open source containerization platform. It enables developers to package applications into containers—standardized executable components combining application source code with the operating system (OS) libraries and dependencies required to run that code in any environment. Containers simplify delivery of distributed applications, and have become increasingly popular as organizations shift to cloud-native development and hybrid multicloud environments.

Developers can create containers without Docker, but the platform makes it easier, simpler, and safer to build, deploy and manage containers. Docker is essentially a toolkit that enables developers to build, deploy, run, update, and stop containers using simple commands and work-saving automation through a single API.

Docker also refers to Docker, Inc. (link resides outside IBM), the company that sells the commercial version of Docker, and to the Docker open source project (link resides outside IBM), to which Docker, Inc. and many other organizations and individuals contribute.


## Required Installation steps and procedures
1)Go to [Docker](https://www.docker.com/products/docker-desktop/) website and download installer for Windows
<img src="https://github.com/najmisaniy/Docker-Tutorial/blob/df659f04a41996fc5a01cf3fb1f6559e9aec185e/Image/Docker%20Page.png">

2)Open docker installer
![installer](/Image/dockerinstaller.png)

3)Tick on Use WSL2 instead of Hyper-V (Add shortcut to desktop is optional)

<img src="https://github.com/najmisaniy/Docker-Tutorial/blob/3acae9d6b4b7845f4f70974a016047946cc8978a/Image/tick%20on.png">

4) Let the installer finish installing the Docker
![installing](/Image/installing.png)



Docker successfully installed

<img src="https://github.com/najmisaniy/Docker-Tutorial/blob/3acae9d6b4b7845f4f70974a016047946cc8978a/Image/install%20succeed.png">

5) Open Docker and accept the agreement
![installing](/Image/aggreement.png)

6) The Docker will start working and pop up will appear if WSL 2 installation is not complete

<img src="https://github.com/najmisaniy/Docker-Tutorial/blob/3acae9d6b4b7845f4f70974a016047946cc8978a/Image/WSAL%202%20INCOMPLETE.png">

7) Click on the [link](https://docs.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package) given and follow the step to install the WSL 2

8) Restart Your Device and Docker is ready to use





## Setup phpMyAdmin and MySQL with Docker
1. Open cmd.exe by pressing “windows” button + “r” button
2. Type mkdir “PMA_docker” to make a phpmyadmin directory named PMA_docker
3. Type “cd PMA_docker’ to change directory to PMA_docker

![step3](/Image/dockerPMAsetup/step3.png)


4. Type “code .” to create a new visual studio code in the directory


![step3](/Image/dockerPMAsetup/step4.png)


Pressing enter will open visual studio code project


![step4](/Image/dockerPMAsetup/step4_2.png)


5. Press the new file icon


![step5](/Image/dockerPMAsetup/step5.png)


6. Name the file docker-compose.yml


![step6](/Image/dockerPMAsetup/step6.png)


7. Fill in the file with the following code:


![step7](/Image/dockerPMAsetup/step7.png)


8. Type “docker-compose up -d” to run service and wait for process to finish


![step8](/Image/dockerPMAsetup/step9.png)


9. Open localhost:8082 on your browser


![step9](/Image/dockerPMAsetup/step10.png)


10. Create new table named library


![step10](/Image/dockerPMAsetup/step11.png)


11. Insert column name, and length


![step11](/Image/dockerPMAsetup/step12.png)


12. Press “insert” button to insert data


![step12](/Image/dockerPMAsetup/step13.png)


13. Insert data and press “go”


![step13](/Image/dockerPMAsetup/step14.png)


14. done 


![step14](/Image/dockerPMAsetup/step15.png)

###
###
