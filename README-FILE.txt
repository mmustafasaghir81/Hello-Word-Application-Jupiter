Step 1 - Install Docker
Docker Desktop Download
https://www.docker.com/products/docker-desktop/
Setp 2 -Create a Project Directory (COMMAND PROMPT)
Create A Directory
  mkdir hello-world-first-application
Change Directory Location
  cd hello-world-first-application
Step 3 - Open Current directory into VSCODE
Step 4 -Create a Jupyter Notebook
Inside this directory, create a Jupyter Notebook file (hello_world.ipynb) with the following content:print("Hello, World!")
Step 05 - Create a Dockerfile (CODE ATTACHED) 
Step 07 - Create a .devcontainer Directory (.devcontainer (Folder)devcontainer.json (File) (CODE ATTACHED)
Step 06 - Build and Run the Docker Container (docker build -t hello-world-jupyter .)
Step 07 - Run the container (docker run -p 8888:8888 hello-world-jupyter)
Step 08-  which will be accessible on your local machine at http://localhost:8888.