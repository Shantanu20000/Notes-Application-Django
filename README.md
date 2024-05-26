# Simple Notes Application
This is a simple Notes Aplplication built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation

Install Docker and Docker-Compose git
```
apt install docker.io docker-compose git -y
```
1. Clone the repository
```
git clone https://github.com/Shantanu20000/Notes-Application-Django.git

```

2. Build the Application
```
docker build -t notes-app .
```

3. Run the Application
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`

`sudo apt install nginx`
