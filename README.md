#Linux Server
This server is being run in a linux environment.
To use it correctly, open in a linux or wsl environment


Tutorial: 
https://medium.com/swlh/deploy-flask-applications-with-uwsgi-and-nginx-on-ubuntu-18-04-2a47f378c3d2


By default, the nginx server runs on: localhost:80/

Guide: 
Before installing applications within the virtual environment, you need to activate it by typing:
source nginx-cellxgene-env/bin/activate

Currently, the server is a development server. Do not use it ina  production deployment. Use a production WSGI server instead. 
