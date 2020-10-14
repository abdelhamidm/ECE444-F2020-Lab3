# ECE444 Lab 4

This repo is a clone of https://github.com/miguelgrinberg/flasky

# Question 2 #

Run Command Screenshot:
<img src="https://github.com/abdelhamidm/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/RunCommand-Screenshot.png">

Webpage Screenshot:
<img src="https://github.com/abdelhamidm/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Webpage-Screenshot.png">

Docker Image Screenshot:
<img src="https://github.com/abdelhamidm/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/DockerImage-Screenshot.png">

The Dockerfile along with the requirements.txt file for this Dockerized application is located in the root folder of this branch. In order to run this application, the first step is to build the Docker image via by entering the following command in terminal:
> docker built -t flask-lab4:latest .

Make sure that the Docker desktop application is running before you enter the build command. 

After building the Docker image, the next step is to run the image. This is done by entering the command that appears in the first screenshot (Run Command Screenshot). 

After building the image and ensuring that it is successfully running via the Docker desktop application, you can access the webpage by going to the following address: 
> 0.0.0.0:5000

# Question 3 #
Docker is a virtualization technology that facilitiates developing, deploying, and managing applications on different systems via containers. They allow applications to run in the same manner regardless of that machine they are running on. Containers are isolated, and, as such, multiple containers can run simultaneouly on a single host. Virtual machines, on the other hand, are isolated computing environments that are created by abstracting resources from a physical machine. In essence, a virtual machine creates a computer within a computer. A virtual machine has its own CPU, memory, network interface, and storage that are provisioned from the physical hardware of the machine running the VM. VMs allow different operating systems to run simultaneously on a single computer. Docker containers are much, much lighter than VMs. 
