# Docker-Bday-Meetup
Pre-requisites for Docker B'Day Meetup

Hello Everyone,

Thanks for registering for this Event. I'm Venkata Nagesh, one of the Mentors for you.
During the meetup, we will have exciting training which includes below.
	- Self-based tutorials which cover basics of docker.
	- Tutorials include building, shipping and running docker containers.
	- Run and develop a cool simple micro-services app.
	- Create your own version of the app and make it available in Docker Hub.

Some of these might be new for you, don't worry, there will be mentors who will guide you through out the process.

To be able to complete the training successfully and get most out of this, we have listed down the pre-requisites which needs be taken care before coming for the meetup.
Please make sure that the below pre-requisites are in place.

1. You need to bring your laptop for doing the training and self-based tutorials.
2. Make sure to create an account in https://hub.docker.com/
3. Download and install Docker toolbox on your laptop.
   For Windows Users: 
	Download link: https://github.com/docker/toolbox/releases/download/v1.10.3/DockerToolbox-1.10.3.exe
	Installation instructions: https://docs.docker.com/windows/step_one/
   For MAC Users:
	Download link: https://github.com/docker/toolbox/releases/download/v1.10.3/DockerToolbox-1.10.3.pkg
	Installation instructions: https://docs.docker.com/mac/step_one/
4. Once Docker toolbox is installed click on "Docker Quickstart Terminal", accept all the pop-up prompts until you get docker image and "$" prompt. 
5. Run the below commands on Docker terminal window to make sure the installation is fine and to download few components which are mandatory for successful training completion.
   $ docker pull hello-world
   $ docker pull busybox
   $ docker pull seqvence/static-site
   $ docker pull mhart/alpine-node
   $ docker pull python:2.7-alpine
   $ docker pull java:openjdk-8-jdk-alpine
   $ docker pull redis:alpine
   $ docker pull postgres:9.4
   $ docker pull java:openjdk-8-jre-alpine 
   $ docker pull java:7
   $ docker pull alpine
   $ docker pull ubuntu:12.04
   $ docker pull node:0.10


6. Open "Oracle VM VirtualBox", you should see "default" machine with status "Running"
   Right-click default on left-side of the window and select "Close" --> "Save state". (You can use Ctrl+V shotcut alternatively)
   You should see the status changed from "Running" to "Saved".
   NOTE: This step is very important. In case if you miss this step, make sure to re-do steps 4,5 and 6 above.

7. You can now close "Oracle VM VirtualBox" and "Docker terminal" windows.

And now you're ready. See you at the Docker B’day Meetup!!

Feel free to reach-out if you have any issues/questions with the pre-requisites.
You can either comment on Meetup or mail at dvnagesh@gmail.com

