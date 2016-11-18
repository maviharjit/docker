# A simple project to Proof of Concept docker-compose

# to build the app and/or bring it up 
docker-compose up

# to tear down the app
docker-compose down

# run the app in daemon mode
docker-compose up -d

# to stop the app if it is running in daemon mode
docker-compose stop

# test the app
browse to http://localhost:5000
hit refresh to increment the counter

# to see runnig containers
docker-compose ps

# to run one off commmand
docker-compose run web env

# if your docker-compose is not latest version and you want to upgrade  
sudo curl -L https://github.com/docker/compose/releases/download/1.9.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

