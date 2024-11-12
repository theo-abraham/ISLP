# ISLP
Applied Statistics from ISLP
How to create a dev environment on Docker: https://www.youtube.com/watch?v=SDa3v4Quj7Y


# dev_container
Template to setup Docker container for Python dev environment 

https://www.youtube.com/watch?v=SDa3v4Quj7Y&t=523s

1. Install VSCode and Docker Desktop
2. Install Remote Development(Microsoft) and Docker extensions on VSCode
3. Create repository on GitHub
4. Go to cmd palette on VSCode and star typing in "Dev Containers..." and click on "Clone Repository in Container Volume"
5. Type in name of repository from GitHub, e.g. "theo-abraham/dev_container" (Make sure you are signed in on GitHub through VSCode)
6. Wait for container to build
7. Add dev container configuration files, what operating system and tools you want to use. Click on "show all definintions" and choose a Python dev environment
8. The parameters of the container will be pulled from the configuration file choosen in the previous step and will create a json file called devcontainer.json that will take the place of the Docker file. Note: use a Docker file if you want to onfigure your own environment instead of using a preconfigured environment
