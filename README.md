# Multi-Container App 

This repo consists of a multi-container app built with Docker.


__Step 1:__
Create a directory named "__multi-container-app__" and use the `cd` command to change your working directory.

__Step 2:__
Within the "__multi-container-app__" directory, create another directory called "__web__". In this "web" directory, creat these files; "__Docker file__", "__app.py__", and "__requirements.txt__".

__Step 3:__
Create a __YAML__ file called "__docker-compose.yml__".
Link the services in the "__docker-compose.yml__" file. This was done with "__depends_on__" and "__host=redis__". This connects the Flask app to the Redis container via Docker's internal DNS.

__Step 4:__
Run and test the app by using the `docker-compose up -build` command.


# Expected Result

The web app should be able to count the number of times the site has been visit.
