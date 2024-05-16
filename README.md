# Controle

## Set Up ans Test Groq API Account Locally

### Recuperation API Key
![MainAPI](https://github.com/Sir22io/Controle/blob/main/Pics/MainAPI.png)


## Set Up ans Dockerize the FastAPI Application

### Local Test with Groq API

Starting on the Local Server

! To test Localy you must change the IP :
from 0.0.0.0 to 127.0.0.1
This way the app launch hitself from your PC
![SRV](https://github.com/Sir22io/Controle/blob/main/Pics/test%20local.png)

Respond on the Web page
![PgeWeb](https://github.com/Sir22io/Controle/blob/main/Pics/Test%20Programme%20Local%20page%20web.png)

## Set up and Dockerize the FastAPI Application

### Set up a Dockerfile and a Installation Script for Python

Creating the Dockerfile
![dockerfile](https://github.com/Sir22io/Controle/blob/main/Pics/Dockerfile.png)

Creating the Python installation script
![SRV](https://github.com/Sir22io/Controle/blob/main/Pics/InstalPy.png)

### We can now test the configuration

We have to build the docker container, lunch the app
#### ! If you are on Windows, don't forget to Run and Start the Docker Descktop App !

Trigger the chat with the command
``` curl -X POST http://localhost:5000/chat      -H "Content-Type: application/json"      -d '{"prompt":"What is the future of AI?"}' ```

Here is the respond from the Chat
![rps](https://github.com/Sir22io/Controle/blob/main/Pics/reponseia.png)

## Create a Development Branch and Implement Testing
