This is a notes app  that is built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

Build the app
docker build -t notes-app .

Run the app
docker run -d -p 8000:8000 notes-app:latest


## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
