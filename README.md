# Docker-Bday-Meetup
Pre-requisites for Docker B'Day Meetup

Hello Everyone,

Thanks for registering for this Event. 
During the meetup, we will have exciting training which includes below.<br>
	- Self-based tutorials which cover basics of docker.<br>
	- Tutorials include building, shipping and running docker containers.<br>
	- Run and develop a cool simple micro-services app.<br>
	- Create your own version of the app and make it available in Docker Hub.<br>

Some of these might be new for you, don't worry, there will be mentors who will guide you through out the process.

To be able to complete the training successfully and get most out of this, we have listed down the pre-requisites which needs be taken care before coming to the meetup.
Please make sure that the below pre-requisites are in place.

1. You need to bring your laptop for doing the training and self-based tutorials.
2. Make sure to create an account in https://hub.docker.com/
3. Download and install Docker toolbox on your laptop.<br>
   For Windows Users: <br>
	Download link: https://github.com/docker/toolbox/releases/download/v1.10.3/DockerToolbox-1.10.3.exe <br>
	Installation instructions: https://docs.docker.com/windows/step_one/ <br>
   For MAC Users: <br>
	Download link: https://github.com/docker/toolbox/releases/download/v1.10.3/DockerToolbox-1.10.3.pkg <br>
	Installation instructions: https://docs.docker.com/mac/step_one/ <br>
   For Linux Users: <br>
	Install Docker Version 1.10.3  <br>
	https://docs.docker.com/engine/installation/linux/fedora/ <br>
	https://docs.docker.com/engine/installation/linux/ubuntulinux/ <br>
	Install Docker-compose version 1.6.2 <br>
	https://docs.docker.com/compose/install/ <br>
	Install git cli <br>
	https://git-scm.com/book/en/v2/Getting-Started-Installing-Git <br>
4. Once Docker toolbox is installed click on "Docker Quickstart Terminal", accept all the pop-up prompts until you get docker image and "$" prompt. 
5. Run the below commands on Docker terminal window to make sure the installation is fine and to download few components which are mandatory for successful training completion. <br>
   $ docker pull hello-world <br>
   $ docker pull busybox <br>
   $ docker pull seqvence/static-site <br>
   $ docker pull mhart/alpine-node <br>
   $ docker pull python:2.7-alpine <br>
   $ docker pull java:openjdk-8-jdk-alpine <br>
   $ docker pull redis:alpine <br>
   $ docker pull postgres:9.4 <br>
   $ docker pull manomarks/worker <br>
   $ docker pull java:openjdk-8-jre-alpine <br> 
   $ docker pull java:7 <br>
   $ docker pull alpine <br>
   $ docker pull ubuntu:12.04 <br>
   $ docker pull node:0.10 <br>


6. Open "Oracle VM VirtualBox", you should see "default" machine with status "Running". <br>
   Right-click default on left-side of the window and select "Close" --> "Save state". (You can use Ctrl+V shotcut alternatively) <br>
   You should see the status changed from "Running" to "Saved". <br>
   NOTE: This step is very important. In case if you miss this step, make sure to re-do steps 4,5 and 6 above.

7. You can now close "Oracle VM VirtualBox" and "Docker terminal" windows. <br>

And now you're ready. See you at the Docker B’day Meetup!! <br>

Feel free to reach-out if you have any issues/questions with the pre-requisites. <br>
You can either comment on Meetup or mail at dvnagesh@gmail.com

